<template>
  <div id="app">
    <navigation />
    <HelloWorld msg="MICHAEL MONTANO B."/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Navigation from './components/Navigation.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    Navigation
  }
}
</script>

<style>
body {
  font-family: 'Barlow Condensed', sans-serif;
  background: #0f1626;
  margin: 0;
  overflow: hidden;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  margin-top: 60px;
}
</style>
