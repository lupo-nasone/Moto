<script setup>
import { RouterView, RouterLink } from "vue-router";    
import { ref } from "vue";
const overflow = ref(true);

let marche = ([
  {
    name: 'Ducati',
    logo: LogoDucati,
    nation: Italia,
    nationa: "Italia",
    nmodelli: "6",
    link: '/ducati',
    numero: 1
  }
])
</script>

<template>
  <div class="container">
    <h1>dio cane</h1>
  </div>
</template>

<style scoped>

</style>
