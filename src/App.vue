<template>
  <div id="app">
    <name></name>
  </div>

</template>

<script>

import name from "./components/MyName.vue"

export default {
  components: {
    name
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
