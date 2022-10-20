<template>
  <div id="app">
    <CalculatorTest />
  </div>
</template>

<script>

import CalculatorTest from './components/CalculatorTest.vue'

export default {
  name: 'App',
  components: {
    CalculatorTest
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
