<template>
  <Header/>
  <br/>
  <br/>
  <br/>
  <br/>
  <br/>
  <br/>
  <h1>Login</h1>
  <div class="login">
    <input type="text" placeholder="Enter Email">
    <input type="text" placeholder="Enter Password">
    <button>Login</button>
  </div>
  <br/>
  <br/>
  <br/>

  <Footer/>

</template>

<script>
import Footer from '@/layout/Footer.vue';
import Header from '../layout/Header.vue';

export default {
    name: 'Login',
    components:{
        Header,
        Footer 
    }
}
</script>

<style>

</style>