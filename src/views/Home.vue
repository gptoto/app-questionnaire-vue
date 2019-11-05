<template>
  <div id="home">
<!--    Ajout d'une image pour remplacer le logo de Vue.js -->
    <img  id="logo" alt="Logo Questions" src="../assets/logo+(62).png" height="100px" width="130px">
    <div id="Accueil">
      <FormCandidat></FormCandidat>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import FormCandidat from '../components/FormCandidat'

// Présentation de la page d'accueil "home" qui contient l'authentification
export default {
  name: 'Home',
  components: {
    FormCandidat
  }
}
</script>


<style scoped>
  html {
    height: 100%;
  }

  #home {
    height: 100%;
    /*background-color: white;*/
    display: grid;
    grid-template-columns: 25% 25% 25% 25%;
    grid-template-rows: 25% 25% 25% 25%;
  }


  #Accueil {
    grid-column: 2/4;
    grid-row: 2/4;
  }
</style>
