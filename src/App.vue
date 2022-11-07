<script>
import AppTitle from "./components/AppTitle.vue";
import AppHero from "./components/AppHero.vue";
export default {
  components: {
    AppTitle,
    AppHero,
  }
}
</script>

<template>
  <div class="container">
    <AppHero />
    <AppTitle />

  </div>

</template>

<style scoped>
.container {
  width: 100%;
  height: 100vh;
}
</style>