<!-- Creare un secondo componente AppHero, che visualizza un jumbotron. -->
<script>
export default {
    data() {
        return {
            imageBanner: "sunset.jpg"
        }
    },
    methods: {
        getImage() {
            return new URL(`../assets/img/${this.imageBanner}`, import.meta.url).href;
        }
    }
}
</script>

<template>
    <div id="banner">
        <img :src="getImage()" alt="Sunset painting">
    </div>
</template>

<style scoped>
#banner {
    height: 30vh;
}

img {
    width: 100%;
    height: 100%;
    object-fit: cover;
}
</style>