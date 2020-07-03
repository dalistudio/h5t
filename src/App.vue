<template>
  <div id="app">
    <topbar></topbar>
    <topheader></topheader>
    <topbanner></topbanner>
    <topfooter></topfooter>
    <!--img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/-->
    
  </div>
</template>

<script>
import topbar from './components/common/topbar.vue'
import topheader from './components/common/topheader.vue'
import topbanner from './components/common/topbanner.vue'
import topfooter from './components/common/topfooter.vue'
//import HelloWorld from './components/HelloWorld.vue'


export default {
  name: 'App',
  components: {
    topbar,
    topheader,
    topbanner,
    topfooter
  }
}
</script>

<style>
@import './assets/css/base.css';

/*
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
*/
</style>
