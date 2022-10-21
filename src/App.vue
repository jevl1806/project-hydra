<template>
  <h1 >Hola Hydra</h1>
  <button @click="changeColor($event)">Cambiar Color</button>
</template>

<script setup lang="ts">
import HelloWorld from './components/HelloWorld.vue'

function changeColor(event: Event): void {
  console.log(event.target)
  return
}

</script>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
