
<template>
  <div class="container">
    <Products />
  </div>
</template>

<script>
  import './style/main.css';
  
  import Vue from "vue";
  import Products from "./Products.vue";

  export default Vue.extend({
    components: {  Products },
  });
</script>

<style scoped>
  .container{
    width: 100%;
    padding-right: 0.75rem;
    padding-left: 0.75rem;
    margin-right: auto;
    margin-left: auto;
  }

  @media (min-width: 576px) {
    .container {
      max-width: 540px;
    }
  }
  @media (min-width: 768px) {
    .container {
      max-width: 720px;
    }
  }
  @media (min-width: 992px) {
    .container {
      max-width: 960px;
    }
  }
  @media (min-width: 1200px) {
    .container {
      max-width: 1140px;
    }
  }
  @media (min-width: 1400px) {
    .container {
      max-width: 1320px;
    }
  }
</style>


