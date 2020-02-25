<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import './assets/sass/app.scss'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style lang="scss">
#app {
  @apply text-center text-gray-700 mt-20 antialiased font-sans;
}
</style>
