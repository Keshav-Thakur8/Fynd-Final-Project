<template>
    <NavigationBar /> 
    <HomeSection />
</template>

<script>
import NavigationBar from './components/NavigationBar.vue'
import HomeSection from './components/HomeSection.vue'

export default {
  name: 'App',
  components: {
    NavigationBar,
    HomeSection
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
  margin-top: 0px;
}
</style>
