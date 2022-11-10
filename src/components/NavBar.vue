<template>

  <section class="src-components-navbar">
    <nav id="navBar" class="navbar navbar-expand-lg navbar-dark bg-dark">
      <router-link to="/">
        <a class="navbar-brand" href="#">Inicio</a>
      </router-link>

      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav">
          <!-- navegacion binding -->
          <li class="nav-item">
            <router-link to="/formulario">
              <a class="nav-link" href="#">Formulario</a>
            </router-link>
          </li>
          <!-- navegacion estructura -->
          <li class="nav-item">
            <router-link to="/http-client">
              <a class="nav-link" href="#">HttpClient</a>
            </router-link>
          </li>
        </ul>
      </div>
    </nav>
  </section>

</template>

<script>

  export default  {
    name: 'src-components-navbar',
    props: [],
    mounted () {

    },
    data () {
      return {

      }
    },
    methods: {

    },
    computed: {

    }
}


</script>

<style scoped lang="css">
a .navbar-brand:hover,.navbar-dark .navbar-nav .nav-link:hover{
  color: brown;
  transition: 1s;
}

#navBar{
  background-color: rgb(61, 62, 63)!important;
}

</style>
