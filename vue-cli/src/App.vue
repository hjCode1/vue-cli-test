<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <app-header></app-header>
  </div>
</template>

<script>
import AppHeader from './components/AppHeader.vue'

export default {
  components: {
    'app-header': AppHeader
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
