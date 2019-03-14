<template>
  <div class="container">
    <div class="row">
      <div class="col-md-7"></div>
      <div class="col-md-5"></div>
    </div>
  </div>
</template>

<script>
import products from '@/products.json';

export default {
  name: 'app',

  data(){
    return{
      products
    }
  }
  
}
</script>

<style>
  
  body {
    background-color: #fbf8f3;
  }
</style>

