<script setup>
import HelloWorld from "./components/HelloWorld.vue";
import MyComponent from "./components/MyComponent.vue";
</script>

<template>
  <header>
    <div class="wrapper">
      <h1>Lab vue setup</h1>
    </div>
  </header>

  <main>
    <MyComponent />
  </main>
</template>

<style scoped>
header {
  line-height: 1.5;
}
h1 {
  color: cornflowerblue;
  font-size: 36px;
  font-weight: bold;
  text-align: center;
}
.logo {
  display: block;
  margin: 0 auto 2rem;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style>
