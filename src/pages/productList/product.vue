<template>
  <div class="product">
    <product-param></product-param>
    <div class="content">
      <p>123</p>
    </div>
  </div>
</template>
<script>
import ProductParam from './../../components/ProductParam'
  export default{
    name:'product',
    data(){
      return {

      }
    },
    components: {
      ProductParam
    }
  }
</script>