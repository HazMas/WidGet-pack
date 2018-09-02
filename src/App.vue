<template>
  <div id="app">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import './assets/css/mycss_lib.css'

export default {
  name: 'app',
  components: {
    HelloWorld
  }
}
</script>

<style lang="scss">
@import url('https://fonts.googleapis.com/css?family=Oswald');
#app {
  font-family: 'Oswald', sans-serif;
}
</style>
