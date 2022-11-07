<script>
import AppTitle from "./components/AppTitle.vue";
import AppHero from "./components/AppHero.vue";
import AppMain from "./components/AppMain.vue";
export default {
  components: {
    AppTitle,
    AppHero,
    AppMain,
  }
}
</script>

<template>
  <div class="container">
    <AppTitle />
    <AppHero />
    <AppMain />
  </div>
</template>

<style scoped>
.container {
  width: 100%;
}
</style>