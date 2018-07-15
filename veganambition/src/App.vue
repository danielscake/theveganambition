<template>
  <div id="app">
<nav class="navbar is-fixed-top">
  <div class="navbar-brand">
    <a class="navbar-item" href="/">
      <img src="./assets/logo.png" alt="Bulma: a modern CSS framework based on Flexbox">
    </a>
    <div class="navbar-burger burger" data-target="navbarExampleTransparentExample">
      <span></span>
      <span></span>
      <span></span>
    </div>
  </div>

  <div id="navbarExampleTransparentExample" class="navbar-menu">
    <div class="navbar-start">

    </div>

    <div class="navbar-end">
      <div class="navbar-item">
      <a class="navbar-item" href="/">
        Home
      </a>
            <a class="navbar-item" href="https://anchor.fm/vegan-ambition">
        Podcast
      </a>
            <a class="navbar-item" href="/about">
        About
      </a>
            <a class="navbar-item" href="/contact">
        Contact
      </a>
      </div>
    </div>
  </div>
</nav>

    <HelloWorld msg=""/>
            <footer class="footer">
  <div class="content has-text-centered">

 <div class="columns is-mobile">
   <div class="column"></div>
      <div class="column"></div>
         <div class="column"></div>
   <div class="column"> <a href="https://www.instagram.com/theveganambition/" ><i class="fab fa-instagram fa-3x"> </i></a></div>
<div class="column"><a href="https://www.facebook.com/veganambitionpodcast/" ><i class="fab fa-facebook fa-3x"> </i></a></div>
<div class="column"><a href="https://www.youtube.com/channel/UCvaYDeHiEZB57gPacYUxwig/"><i class="fab fa-youtube fa-3x"> </i></a></div>
   <div class="column"></div>
      <div class="column"></div>
         <div class="column"></div>


</div>
    <p>
      <strong>theveganambition</strong> by <a href="https://danielruginets.com"><strong>daniel ruginets. </strong></a> <strong><a href="mailto:veganambitionpodcast@gmail.com">email us. </a></strong> <strong>circa 2018.</strong>
      </p>
 <br>



  </div>
</footer>
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
  color: #4C4C4C;
  margin-top: 60px;
}
html{
  background: #fdf5f8 !important;
}

.logo{
  width:40%;
}

</style>
