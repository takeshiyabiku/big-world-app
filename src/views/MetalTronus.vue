<template>
    <div class="app-container">
      <div class="main-content-container">
            <CartaA />
            <CartaB />
      </div>
    </div>
  </template>
  
  <script>
  import CartaA from '../components/CartaA.vue';
  import CartaB from '../components/CartaB.vue';

  
  export default {
    name: 'MetalTronus',
    components: {
     CartaA,
     CartaB
    }
  };
  </script>
  
  <style scoped>
  @import '/src/App.css'; /* Importa o arquivo CSS */
  </style>