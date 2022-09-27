<template>
  <div>
    <img
      src="https://concepto.de/wp-content/uploads/2018/08/monta%C3%B1as-e1533762816593.jpg"
      alt=""
    />
    <h1>{{ myText }}</h1>
    <button @click="helloWorld()">Click ME</button>
    <button @click="helloWorld2">Alert</button>
  </div>
</template>

<script setup>
import { ref } from "vue";
let myText = ref("Hike more Worry less");

function helloWorld() {
  console.log("Happiness");
}
const helloWorld2 = () => {
  alert("Happiness");
};
</script>

<style scoped>
h1 {
  color: cornflowerblue;
  text-align: center;
}
button {
  background-color: cornflowerblue;
  width: 100px;
  padding: 15px;
  align-items: center;
}
</style>
