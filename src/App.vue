<template>
  <div id="app">
    <Title msg="La mia prima app con Vue CLI!"/>
    
    <Hero msg="Ci ho provato, volevo caricare un'immagine ma rinuncio, questo sarà il mio jumbotron fino a domani"/>
  </div>

</template>

<script>
import Title from './components/Title.vue'
import Hero from './components/Hero.vue'

export default {
  name: 'App',
  components: {
    Title,
    Hero
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
