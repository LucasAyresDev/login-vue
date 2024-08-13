<script setup>
import HelloWorld from './components/HelloWorld.vue'
import ComponentTest from './components/ComponentTest.vue'
</script>

<template>
  <div class="wrapper">
    <HelloWorld />
  </div>
  <div>
    <ComponentTest />
  </div>
</template>

<style scoped>
.wrapper {
  background: linear-gradient(to right, #74cbe0, #1b1b1b);
  width: 100vw; /* 25% da largura da viewport */
  height: 100vh;
  margin: 0; /* Remover margens */
  padding: 0; /* Remover preenchimentos */
  border: none; /* Remover bordas, se houver */
}
</style>
