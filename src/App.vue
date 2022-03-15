<template>
<app-nav-bar :url = "this.title"></app-nav-bar>
  <router-view/>
</template>
<script>
import Navbar from '../src/components/Navbar.vue'
export default{
  components:{
    appNavBar: Navbar
  },
  data(){
    return{
      title: 'what are you doing here'
    }
  }
}
</script>
<style>
body{
  background: #f2f2f2;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  max-width: 600px;
  margin:0 auto;
  color: #555;
}
</style>
