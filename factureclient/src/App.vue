<template>
  <div id="app">
    <accueil msgAccueil="Bienvenu sur la page d'accueil de l'API de facturation BENETEAU"/>
  </div>
</template>

<script>
import accueil from './components/accueil.vue'

export default {
  name: 'app',
  components: {
    accueil
  }
}
</script>

<style>
#app {
  font-size:2vh;
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
#app  {
  font-size:2vh;
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
