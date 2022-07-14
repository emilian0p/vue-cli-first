<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <TitleContent msg=""/>
    <HeroJumbo msg=""/>
  </div>
</template>

<script>
import TitleContent from './components/TitleContent.vue'
import HeroJumbo from './components/HeroJumbo.vue'

export default {
  name: 'App',
  components: {
    TitleContent,
    HeroJumbo
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
