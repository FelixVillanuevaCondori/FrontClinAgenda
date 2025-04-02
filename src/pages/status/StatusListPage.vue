<script setup lang="ts">
import { DefaultTemplate } from '@/template'
const ItensDaTabela = [
  {
    name: 'African Elephant',
    species: 'Loxodonta africana',
    diet: 'Herbivore',
    habitat: 'Savanna, Forests'
  }
  // ... more items
]
</script>

<template>
  <DefaultTemplate>
    <v-data-table :items="ItensDaTabela"></v-data-table>
  </DefaultTemplate>
</template>
