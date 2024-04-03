<script setup>
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
</script>

<template>
  <header>
    <img alt="Vue logo" class="logo" src="./assets/foto1.png" width="165" height="155" />

    <div class="wrapper">
      <HelloWorld msg="Daztyn Daffa Danendra!" />
    </div>
  </header>

  <main>
    <TheWelcome />
  </main>
</template>

<style scoped>
header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin-top: 220px;
  margin-left: 100px;
  margin-bottom: 40px;
  border-radius: 50%;
}
</style>
