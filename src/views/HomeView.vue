<script setup>
import MonBouton from "../components/MonBouton.vue";
import MonTitre from "../components/MonTitre.vue";
</script>

<template>
  <main>
    <MonTitre :niveau="1">Bonjour !</MonTitre>
    <MonTitre :niveau="2">Boutons :</MonTitre>
    <MonBouton type="primary">clic!</MonBouton>
    <MonBouton type="secondary">clic!</MonBouton>
    <MonBouton type="danger">clic!</MonBouton>
  </main>
</template>
