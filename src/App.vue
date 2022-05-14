<template>
  <Background/>
  <HelloWorld msg="PACIFIC OCEAN"/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Background from './components/Background.vue'


export default {
  name: 'App',
  components: {
    HelloWorld,
    Background
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: white;
  margin-top: 60px;
}
</style>
