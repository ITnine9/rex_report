<template>
  <div id="app">
    <BlueHeader></BlueHeader>
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
  </div>
</template>

<script>
import BlueHeader from './components/BlueHeader'

export default {
  name: 'App',
  components: {
    // HelloWorld
    BlueHeader
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
  /* margin-top: 60px; */
}
</style>
