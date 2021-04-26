<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your Vue.js App haha  dddddddđ"/>
  <br/>
  <User msg="Welcome to User"/>

  <h1> hello USer</h1>

</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import User from './components/User.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    User
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
