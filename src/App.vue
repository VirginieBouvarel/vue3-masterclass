<template>
  <img alt="Vue logo" src="./assets/logo.png" width="125" height="125">
  <div class="container">
    <PageHome />
  </div>
</template>

<script>
import PageHome from '@/components/PageHome.vue';

export default {
  name: 'App',
  components: {
    PageHome,
  }
}
</script>

<style>
  @import 'assets/style.css';
</style>
