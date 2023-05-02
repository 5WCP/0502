<script setup>
  import Footer from "./components/Footer.vue";
  import Header from "./components/Header.vue";
</script>

<template>
  <div class="container">
    <Header />
    <Footer />
  </div>
</template>

<style scoped>
.container {
  width: 100vw;
  height: 100vh;
  background-color: #c2baba;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
}
</style>
