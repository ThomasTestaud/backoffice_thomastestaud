<template>
    <div class="gallerie photo">
      <h1>Decoration d'intérieur</h1>
      <img src="../assets/1.png" alt="Salut">
      <img src="../assets/2.png" alt="nope">
      <img src="../assets/3.png" alt="Salut">
      <img src="../assets/4.png" alt="nope">
      <img src="../assets/5.png" alt="Salut">
      <img src="../assets/6.png" alt="nope">
      <img src="../assets/7.png" alt="Salut">
      <img src="../assets/8.png" alt="nope">
      <img src="../assets/9.png" alt="Salut">
    </div>
  </template>
  
  <script>
  export default {
    name: 'GallerieComponent'
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