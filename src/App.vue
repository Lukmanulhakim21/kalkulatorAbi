<template>
  <div id="app">
    <heading/>
    <kalkulator/>
  </div>
</template>

<script>
import heading from './components/heading.vue'
import kalkulator from './components/kalkulator.vue'

export default {
  name: 'App',
  components: {
    heading,
    kalkulator
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
  margin-top: 30px;
}
</style>
