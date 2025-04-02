<script setup lang="ts">
import { DefaultTemplate } from '@/template'
</script>

<template>
  <DefaultTemplate>
    <template #default>
      <div class="dashboard"></div>
    </template>
  </DefaultTemplate>
</template>

<style scoped>
.dashboard {
  max-width: 600px;
  margin: auto;
}

.dashboard svg {
  width: 100%;
}
</style>
