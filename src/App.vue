<template>
  <BaseLayout>
  <template #header>
    <h1>Here might be a page title.</h1>
  </template>  
  <template #main>
    <p>
      A paragraph of main content.
    </p>
    <p>
      And another one.
    </p>
  </template>  
  <template #footer>
    Here's some contact info.
  </template>  
  </BaseLayout>
</template>

<script setup>
import BaseLayout from './BaseLayout.vue'
</script>

<style lang="scss" scoped>

</style>