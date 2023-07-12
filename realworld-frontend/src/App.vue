<script setup lang="ts">
</script>

<template>
  <router-link :to="{ path: '/'}">Home</router-link> | <router-link :to="{ name: 'About' }">About</router-link>
  <RouterView />
</template>

<style scoped>
</style>
