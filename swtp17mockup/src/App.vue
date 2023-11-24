<template>
 <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
  <HowToTest msg="Welcome to Your Vue.js App"/>
  <HelloWorld msgs="this String will be sent to the component <template>"/>
</template>

<script>
import HowToTest from './components/HowToTest.vue'
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HowToTest,
    HelloWorld
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
