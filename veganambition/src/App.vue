<template>
  <div id="app">
    <nav class="level">
  <p class="level-item has-text-centered">
    <a class="link is-info">Home</a>
  </p>
  <p class="level-item has-text-centered">
    <a class="link is-info">Menu</a>
  </p>
  <p class="level-item has-text-centered">
    <img src="./assets/logo.png" alt="" style="height: 130px;">
  </p>
  <p class="level-item has-text-centered">
    <a class="link is-info">Reservations</a>
  </p>
  <p class="level-item has-text-centered">
    <a class="link is-info">Contact</a>
  </p>
</nav>
    <HelloWorld msg=""/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'



export default {
  name: 'app',
  components: {
    HelloWorld
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
html{
  background: #fdf5f8 !important;
}

.logo{
  width:30%;
}

</style>
