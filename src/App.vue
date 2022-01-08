<template>
  <div id="app">
    <div class="container-fluid">
      <div class="row align-items-center justify-content-center py-5" style="min-height: 100vh">
        <Card msg=""/>
      </div>
    </div>
  </div>
</template>

<script>
import Card from './components/Card.vue'

export default {
  name: 'App',
  components: {
    Card, 
  }
}
</script>

<style>
#app {
  font-family: Outfit, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  background-color: hsl(217, 54%, 11%);
}
</style>
