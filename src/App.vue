<template>
  <div class="container" id="app">
    <h3>{{ message }}</h3>
  </div>
</template>

<script>
  export default {
    name: 'app',
    data () {
      return {
        message: 'Vue.js App is LIVE!'
      }
    }
  }
</script>

<style lang="css">
  #app {
    color: green;
  }
</style>