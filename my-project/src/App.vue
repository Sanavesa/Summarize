<template>
  <div id="app">
    <!-- <img src="./assets/logo.png"> -->
    <!-- <HelloWorld/> -->
    <HomePage/>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld'
import HomePage from './components/HomePage'

export default {
  name: 'App',
  components: {
    HomePage
    // HelloWorld
  }
}
</script>

<style>
/*#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}*/
</style>
