<template>
  <h1>ทดสอบ app component</h1>
  <ListCustomer/>
  <ListDashboard/>
  <!-- <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your Vue.js App"/> -->
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'
import ListCustomer from './components/ListCustomer.vue';
import ListDashboard from './components/ListDashboard.vue';
export default {
  name: 'App',
  // components: {
  //   HelloWorld
  // }
    components: {
      ListCustomer, 
      ListDashboard

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
