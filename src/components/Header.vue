<template>
  <h1>Hello {{ name }}</h1>

  <button @click="helloWorld()">Button</button>
</template>

<script setup>
import { ref } from "vue";
let name = ref("pier");
function helloWorld() {
  console.log("Hello world");
}
</script>
<style></style>