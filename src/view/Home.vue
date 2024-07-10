<template>
  <img alt="Vite logo" width="120" src="../assets/vite.svg" />
  <img alt="Vue logo" width="120" src="../assets/logo.png" />
  <img alt="Electron logo" width="120" src="../assets/electron.png" />
  <img alt="TS logo" width="120" src="../assets/ts.png" />
  <HelloWorld msg="Vite + Vue 3 + Electron + TypeScript" />
  <br />
  <p class="plugins">Plugins</p>
  <img alt="vue router logo" width="120" src="../assets/vueRouter.png" />
  <img alt="pinia logo" width="120" src="../assets/pinia.svg" />
</template>

<script setup lang="ts">
import HelloWorld from "../components/HelloWorld.vue";
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
img {
  margin: 5px;
}
.plugins {
  font-size: 20px;
  font-weight: bold;
  margin-top: 20px;
}
</style>