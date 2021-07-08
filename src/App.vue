<template>
  <div id="app">
    <Navbar />
    <router-view></router-view>
  </div>
</template>

<script>
import Navbar from './components/Navbar.vue'

export default {
  name: 'App',
  components: {
    Navbar
  },
  calculated: {
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  height: 98%;
  margin: 1% 2%;
  background-color: whitesmoke;
}
html, body {
  height: 100%;
  display: flex;
  flex-direction: column;
  background-color: #EBD5B3;
}
</style>
