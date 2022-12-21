<template>
  <div class="flex flex-col lg:flex-row min-h-screen font-Roboto bg-weather-secondary">
    <SiteNav />
    <RouterView />
  </div>
</template>

<script setup>
import { RouterView } from 'vue-router';
import SiteNav from './components/SiteNav.vue';
</script>

<style lang="scss" scoped>

</style>