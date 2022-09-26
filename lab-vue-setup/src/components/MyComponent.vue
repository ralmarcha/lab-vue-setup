<template>
  <div>
    <h1>{{ myText }}</h1>
    <button @click="helloWorld">Click ME</button>
  </div>
</template>

<script setup>
import { ref } from "vue";
let myText = ref("This is my text interpolation");

let app = new Vue({
  methods: {
    helloWorld() {
      console.log("Hello");
    },
  },
});
</script>

<style scoped></style>
