<template>
  <div id="app">
    <router-view></router-view>
    <landing-page></landing-page>
  </div>
</template>

<script>
  import LandingPage from '@/components/LandingPage'
  export default {
    name: 'app',
    components: {
      LandingPage
    }
  }
</script>

<style>
  /* CSS */
</style>