<template>
  <div class="container-fluid mt-3">
    <div class="jumbotron">
      <h1>PNT2 - TP4</h1>
      <br>
  
      <NavBar/>
      <router-view></router-view>

      <br>
      <br>

      <h2>Alumno: Maximiliano Malek</h2>
  
  
    </div>
  </div>
  </template>
  
  <script>
  
  import NavBar from './components/NavBar.vue'
  
  
  export default {
    name: 'App',
    components: {
       NavBar
    }
  }
  </script>
  
  <style>
    h1,h2 {
      color: rgb(174, 164, 158);
    }
    div .jumbotron{
      background-color: rgb(42, 35, 35);
    }

    div .container-fluid{
      background-color: blanchedalmond;
    }

  </style>