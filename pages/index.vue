<script setup lang="ts">
const handleMessage = () => {
  message.info("This is a normal message");
}
definePageMeta({
  layout: 'admin-layout'
})

</script>

<template>
  <span>index</span>
  <a-button @click="handleMessage">
    button
  </a-button>
</template>

<style scoped>

</style>