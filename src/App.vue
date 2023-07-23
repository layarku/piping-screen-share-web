<template>
  <v-app id="app">
    <h1>Jambul PE</h1>
    <hr>
    <PipingScreenShare />
  </v-app>
</template>

<script setup lang="ts">
import PipingScreenShare from './components/PipingScreenShare.vue';

</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  padding-top: 60px;
}
</style>
