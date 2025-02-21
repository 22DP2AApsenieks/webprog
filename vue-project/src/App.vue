<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
import Footer from './components/Footer.vue';
import Header from './components/Header.vue';
</script>

<template>
  <Header/>
  <body>
    <RouterLink to="/">Home</RouterLink>
    <RouterLink to="/about">About</RouterLink>
    <RouterLink to="/super">super index</RouterLink>
    <RouterView />
  </body>
  <Footer />
</template>

<style scoped>

</style>
