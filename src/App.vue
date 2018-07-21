<template>
  <div id="app">
    <img src="./assets/logo.png">
    <image-selector/>
  </div>
</template>

<script>
import ImageSelector from './components/ImageSelector.vue'

export default {
  name: 'app',
  components: {
    ImageSelector
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
