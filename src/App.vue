<!-- javascript -->
<script>
// riferimento a AppTitle.vue
import primoComponenente from './components/AppTitle.vue';

// riferimento a AppHero.vue
import secondoComponenente from './components/AppHero.vue';

//Definizione del componente nella pagina
export default {
  components: {

    // riferimento a AppTitle.vue
    primoComponenente,

    // riferimento a AppHero.vue
    secondoComponenente
  }
}
</script>


<!-- html -->
<template>
  <!-- inserisco nel template l'elemento title -->

  <!-- riferimento a AppHero.vue -->
  <primoComponenente />

  <!-- riferimento a AppHero.vue -->
  <secondoComponenente />
</template>


<!-- CSS -->
<style></style>
