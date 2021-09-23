<template>
  <div class="navbar">
    <nav class="navbar-extended blue darken-2">
      <div class="nav-content">
         <!-- <img src="https://media.istockphoto.com/vectors/smoothie-flat-design-naturopathy-icon-with-side-shadow-vector-id925601864?b=1&k=20&m=925601864&s=612x612&w=0&h=g1uIYIYlWLwGG5nfYXBdlWO1t5WTDy4g3zQ3KUifkWo="> -->
          <router-link to="">
              <span class="nav-title"> Tong Wei 佟维 Smoothies</span>
          </router-link>
          <a href="" class="btn-floating btn-large halfway-fab red">
             <router-link to="">
                <i class="material-icons">add</i>
             </router-link>
          </a>
      </div>
    </nav>
  </div>
</template>

<script>
export default {
  name: 'Navbar',
  data () {
    return {

    }
  }
}
</script>

<style scoped>
.navbar nav
{
  padding:0 20px;
  height: 20%;
  }

  img{
  height: 20%;
  width:20%;
  }
</style>
