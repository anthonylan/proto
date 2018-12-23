<template>
  <div id="app">
    <nav id="nav">
      <router-link to="/" class="logo-text">Proto.css</router-link>
       <a href="https://github.com/anthonylan/proto" target="_blank" class="github">View on Github</a>
      
    </nav>
    <router-view />

    <Docs />
  </div>
</template>



<script>

import Home from './views/Home.vue'
import Docs from './views/Docs.vue'


export default {
  name: 'app',
  components:{
    Home,
    Docs
  },
  data(){
    return{

    }
  }
}
</script>


<style lang="scss">
@import url('https://fonts.googleapis.com/css?family=Quicksand:300,400,700');
$dark-main: rgb(44, 62, 80);
.container{
  width: 70%;
  margin: 0 auto;
  @media (max-width:550px) {
    width: 80%;
  }
}
#app {
  font-family: 'Quicksand', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
#nav {
  padding: 30px;
  margin-bottom: 40px;
  a {
    font-weight: 400;
    color: $dark-main;
    text-decoration: none;
    font-size: 1rem;
    margin: 0;
    text-transform: uppercase;
    font-weight: bold;
  }
  .github{
    float: right;
  }
}




/*PROTO*/


</style>
