<script>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup
import Header from './components/Header.vue'
import Footer from './components/Footer.vue'
export default{
  components:{
    Header,
    Footer,
  }
}

</script>

<template>
  <Header/>

  <img src="./assets/coming-soon-blog.png" class="imgCom" alt="">
  
  <Footer />
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin: 0;
  padding: 0;
}
.imgCom{
  width: 100%;
}
</style>
