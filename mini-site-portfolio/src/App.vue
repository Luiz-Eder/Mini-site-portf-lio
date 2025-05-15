<script setup>
import NavigationBar from './components/NavigationBar.vue'
import SimpleFooter from './components/Footer.vue' 
</script>

<template>
  <div class="min-h-screen flex flex-col">
    <NavigationBar />
    
    <main class="flex-grow">
      <router-view /> 
    </main>
    
    <SimpleFooter />
  </div>
</template>