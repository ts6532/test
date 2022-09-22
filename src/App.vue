<script setup lang="ts">
import HelloWorld from "./components/HelloWorld.vue";
</script>

<template>
  <div class="flex gap-5 justify-center my-10">
    <a href="https://vitejs.dev" target="_blank">
      <img src="/vite.svg" class="logo" alt="Vite logo" />
    </a>
    <a href="https://vuejs.org/" target="_blank">
      <img src="./assets/vue.svg" class="logo vue" alt="Vue logo" />
    </a>
  </div>

  <section class="grid grid-cols-3 gap-5">
    <div v-for="block in 10" :key="block" class="w-full h-24 bg-red-500"></div>
  </section>
</template>

<style scoped></style>
