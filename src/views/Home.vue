<template>
  <div class="home">
    <div class="wrapper">
    <img class="logo" src="../assets/logo.png" alt="logo">
    <h2>Prototyping made easy</h2>
    <a href="https://github.com/anthonylan/proto/tree/master/src/proto/proto.css" class="download" download>Download</a>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src


export default {
  name: 'home',
  data(){
    return{

    }
  },
  methods:{

  }
}
</script>

<style lang="scss" scoped>
$primary: #42c9fc;
.home{
  display: table;
  height: 100%;
  width: 100%;
  .wrapper{
    display: table-cell;
    text-align: center;
    vertical-align: middle;
  }
  .logo{
    width: 16rem;
  }
  h2{
    font-size: 3rem;
    color: #333;
    font-weight: lighter;
  }
  .download{
    display: inline-block;
    background: #f8f9f9;
    color: #2c3e50;
    padding: 1.1rem 2rem;
    text-decoration: none;
    font-size: 1.5rem;
    border-radius: 50px;
    border: 1px solid #ddd;
    box-shadow: 0px 5px 5px -2px #eaeded;
    transition: all .2s ease-in-out;
    font-weight: 400;
    cursor: pointer;
    &:hover{
      box-shadow: 0px 3px 3px -2px #eaeded;
    }
  }
}
</style>
