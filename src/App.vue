<template>
  <div id="app">
    <Navbar />
    <Home/>
  </div>
</template>

<script>
import Navbar from './components/Navbar.vue'
import Home from "./components/Home"

export default {
  name: 'App',
  components: {
    Navbar,
    Home
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body{
  background: #ffffff;
}
</style>
