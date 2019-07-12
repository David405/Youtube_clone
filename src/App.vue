<template>
  <div id="app">
      <img style="width:140px; margin:14px;" src="./assets/logo.png"/> 
    <HelloWorld/>
  </div>
</template>

<script>
import HelloWorld from './components/VideoPlayer'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
