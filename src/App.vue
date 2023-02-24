<!-- javascript -->
<script>
// riferimento a AppTitle.vue
import primoComponenente from './components/AppTitle.vue';

//Definizione del componente nella pagina
export default {
  components: {
    primoComponenente
  }
}
</script>


<!-- html -->
<template>
  <!-- inserisco nel template l'elemrnto title -->
  <primoComponenente />
</template>


<!-- CSS -->
<style></style>
