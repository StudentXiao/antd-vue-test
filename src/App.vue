<template>
  <div id="app">
    <test />
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import Test from './components/test.vue'

export default {
  name: 'App',
  components: {
    Test
    // HelloWorld
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
