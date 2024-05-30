<script>

import AppTitle from './components/AppTitle.vue';
import AppHero from './components/AppHero.vue'

export default {
  components: {
    AppTitle,
    AppHero,
  }
}

</script>

<template>
  <AppTitle />
  <AppHero />
  <p>Sono il resto della pagina, ma sono di colore rosso</p>
</template>

<style scoped>
  p {
    color: red;
  }
</style>
