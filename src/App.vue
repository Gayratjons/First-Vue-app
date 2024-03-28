<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <New />
</template>

<script>
import New from './components/New.vue'

export default {
  name: 'App',
  components: {
    New
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
}
</style>
