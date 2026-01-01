<script setup>
  import Header from '@/components/Header.vue'
  import Main from '@/components/Main.vue'
  import Footer from '@/components/Footer.vue'
</script>

<template>
  <div class='wrap'>
    <div class='app'>
      <Header />
      <Main />
      <Footer />
    </div>
  </div>
</template>

<style scoped>
  .wrap {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    height: 100vh;
  }
  .app {
    display: flex;
    flex-direction: column;
    align-items: center;
    max-width: 25rem;
    width: 100%;
    height: 100vh;
    text-align: center;
    margin-top: 4rem;
  }
</style>
