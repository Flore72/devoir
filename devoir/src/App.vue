

<template>
 <header>
  <nav class = "menu">
  <img alt="./assets/Photos/logo BCS.png" :src="require('./assets/Photos/logo BCS.png')" />
  <a href = "Contact.vue" target ="_blanck"><h2>Contact</h2></a>
  <a href = "Informations.vue" target="_blank"><h5>Informations</h5></a>
  <a href = "Nos_travaux..vue" target ="_blanck"> <h2>Nos travaux</h2></a>

  </nav>
</header>

<footer>
   
   <a href = "https://github.com/Flore72/Portfolio.git" target = "_blanck"><img src = "./assets/Photos/github.png" alt = "github"></a>
   <a href = "linkedin.html" target = "_blanck"><img src = "./assets/Photos/linkedin.png" alt = "linkedin"></a><br>
   

</footer>


  <RouterView />
</template>


<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
const app = Vue.createApp({RootComponent}).mount("#app")
    console.log(app)

<script>
       document.write("Dernière mise à jour : " + document.lastModified);
</script>
<style scoped>

</style>
