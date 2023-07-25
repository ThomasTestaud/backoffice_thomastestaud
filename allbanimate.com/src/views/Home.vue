<template>
      <h1>Peintures disponible</h1>
      <img src="../assets/8.png" alt="Salut">
      <img src="../assets/9.png" alt="nope">
      <img src="../assets/4.png" alt="Salut">
  </template>
  
  <script>
  export default {
    name: 'HomeComponent'
  }
  </script>
  
  <!-- Add "scoped" attribute to limit CSS to this component only -->
  <style scoped>
    img {
      width: 30rem;
      height: 30rem;
      object-fit: cover;
      margin: 1rem;
    }
  </style>