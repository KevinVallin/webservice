<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <ClientView msg="Welcome to Your Vue.js App"/>
</template>

<script>
import ClientView from './components/ClientView.vue'

export default {
  name: 'App',
  components: {
    ClientView
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
