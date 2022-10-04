<template>
  <div id="app">
  <!-- <products-main /> -->
  <!-- <user-comp /> -->
  <main-assign />


  </div>
</template>

<script>
import MainAssign from './components/Main-assign.vue'
// import UserComp from './components/UserComp.vue'
// import ProductsMain from './components/Products-main.vue'

export default {
  name: 'App',
  components: {
    MainAssign
    // UserComp
  //  ProductsMain
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
}
</style>
