<template>
  <div class="accueil">
    <h1>{{ msgAccueil }}</h1>
    <p>Bienvenue sur l'API de facturation de l'entreprise BENETEAU cette application à pour but de fournir des information sur les factures et fournisseurs de l'entreprise en fonction des critère choisi par l'utilisateur.<br><br>
    Pour commencer à naviguer vous pouvez cliquer sur le bouton "FOURNISSEUR" pour avoir la liste des fournisseurs ou sur le bouton "FACTURE" pour accéder à la liste des factures.
    </p>

  </div>
</template>

<script>
export default {
  name: 'accueil',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
