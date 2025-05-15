<template>
<nav class="bg-gradient-to-r from-blue-700 via-indigo-900 to-black-500 p-4"> 
    <div class="flex h-10">
      <router-link 
        to="/" 
        class="text-white hover:bg-black-700 px-3 py-2 rounded"
      >
        Inicio
      </router-link>
      <router-link 
        to="/sobre" 
        class="text-white hover:bg-black-700 px-3 py-2 rounded"
      >
        Sobre
      </router-link>
      <router-link 
        to="/contato" 
        class="text-white hover:bg-black-700 px-3 py-2 rounded"
      >
        Contato
      </router-link>
    </div>
  </nav>
</template>