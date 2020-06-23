<template>
  <div>Vite Router</div>
  <div class="nav">
    <router-link to="/home">Home</router-link>
    <router-link to="/user/12">User</router-link>
    <router-link to="/desc">Desc</router-link>
    <router-link to="/about">About</router-link>
  </div>
  <router-view></router-view>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>
  .nav {
    padding: 10px;
  }
  .nav a {
    margin: 10px;
  }
</style>