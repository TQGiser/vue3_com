<template>
  <CvP1/>
  <CvP2/>
</template>

<script>
import CvP1 from './components/CvP1.vue'
import CvP2 from './components/CvP2.vue'

export default {
  name: 'App',
  components: {
    CvP1,
    CvP2
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
