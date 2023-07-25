<template>
  <div class>
  <img alt="ranterspacelogo" src="./assets/logo.png">
  <topPart />
  </div>
</template>

<script>
import topPart from './components/topPart.vue'

export default {
  name: 'App',
  components: {
    topPart
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
