<template>
  <div id="app">

    <HeyBabe />
  </div>
</template>

<script>
import HeyBabe from './components/HeyBabe.vue'

export default {
  name: 'app',
  components: {
    HeyBabe
  }
}
</script>

<style>
html, body {
  margin: 0;
  padding: 0;
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin: 0;
  padding: 0;
  height: 100vh;
  background-image: url("./assets/babenoir.jpg");
  background-size: cover;
  background-position: 50%;
}
</style>
