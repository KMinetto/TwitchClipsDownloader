<template>
  <HelloWorld />
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>
#app {
  width: 100%;
  height: 100%;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #f6f6f6;
  font-weight: bold;
}
</style>
