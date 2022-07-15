<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <TitleMain msg=""/>
    <JumboTron msg=""/>
  </div>
</template>

<script>

import TitleMain from './components/TitleMain.vue';
import JumboTron from './components/JumboTron.vue';

export default {
  name: 'App',
  components: {
    TitleMain,
    JumboTron
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
