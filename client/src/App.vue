<script setup>
import HelloWorld from "./components/HelloWorld.vue";
import rocketLogo from "./assets/rocket.png";
</script>

<template>
  <div>
    <img :src="rocketLogo" class="logo" alt="Discord" />
    <HelloWorld msg="Hello World, Vue.js" />
  </div>
</template>


