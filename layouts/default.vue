<template>
  <div>
    <navbar></navbar>
    <nuxt/>
    <my-footer/>
  </div>
</template>

<script>
  import Navbar from '../components/Navbar'
  import MyFooter from '../components/Footer.vue'

  export default {
    components: {
      Navbar,
      MyFooter
    }
  }
</script>

<style>
  html {
    font-family: "Source Sans Pro", "Helvetica Neue", Arial, sans-serif;
    height: 100%;
  }

  footer {
    text-align: center;
    padding: 30px 0;
    background: #eee;
  }
</style>