<template>
  <div id="app">
  <img src="./assets/logo.png">
  </div>
</template>

<script>
import Home from './components/Home'
export default {
  name: 'app',
  components: {
    Home
  }
}
</script>
<!-- styling for the component -->
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
