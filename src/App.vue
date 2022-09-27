

<template>

 <div class="main w-full  pl-6 pr-6 pt-2 pb-36">
  <Head />
  <Cswiper />
  <HotGame />
  <UserName />
  <Hobbies />
  <Footer />
 </div>
  <!-- <HelloWorld msg="Vite + Vue" /> -->
</template>

<script setup>

  // import HelloWorld from './components/HelloWorld.vue'
  import Head from './components/Head.vue';
  import Cswiper from './components/Cswiper.vue';
  import HotGame from './components/HotGame.vue';
  import UserName from './components/UserName.vue';
  import Hobbies from './components/Hobbies.vue';
  import Footer from './components/Footer.vue';
  </script>

<style scoped>
.main{
  background-color: rgb(26 26 26 / 1);
  font-family: ui-sans-serif,system-ui,-apple-system,BlinkMacSystemFont,Segoe UI,Roboto,Helvetica Neue,Arial,Noto Sans,sans-serif,"Apple Color Emoji","Segoe UI Emoji",Segoe UI Symbol,"Noto Color Emoji";
    
}
</style>