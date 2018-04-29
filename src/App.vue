<template lang="html">
  <div class="container">
    <app-header></app-header>
    <div class="row">
      <div class="col-xs-12">
        <router-view></router-view> <!-- Portfolio and Stock Template will goes here -->
      </div>
    </div>
  </div>
</template>

<script>
  import Header from './components/Header.vue';
  export default {
      components: {
        appHeader: Header
      }
  }
</script>

<style lang="css">
  body {
    padding: 30px;
  }
</style>
