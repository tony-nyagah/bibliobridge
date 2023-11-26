<script setup lang="ts">
  const version: number = 3;
</script>

<template>
  <div class="hello">
    <p class="text-red-500">Hello Nuxt {{ version }}</p>
  </div>
</template>

<style scoped>
  .hello {
    font-family: Arial, Helvetica, sans-serif;
    font-size: 3rem;
    padding: 2rem;
  }
</style>
