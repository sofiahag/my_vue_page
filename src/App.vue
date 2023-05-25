<script setup>
import NavBar from './components/NavBar.vue'
import MainContent from './components/MainContent.vue'
import CodeFooter from './components/CodeFooter.vue'
</script>

<template>
  <main>
    <div class="content">
      <NavBar/>
      <MainContent/>
      <CodeFooter/>
    </div>
  </main>
</template>

<style scoped>

.content {
  text-align: center;
  margin: 0;
} 

</style>
