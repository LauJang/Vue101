<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <ClickCounter title="Click Counter"/>
  </div>
</template>

<script>
import ClickCounter from './components/ClickCounter.vue'

export default {
  name: 'App',
  components: {
    ClickCounter
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
