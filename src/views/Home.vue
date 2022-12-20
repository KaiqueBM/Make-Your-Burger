<template>
  <div class="main-container">
    <Banner />
    <BurgerForm id="main-burgerform" />
  </div>
</template>

<script>
import Banner from '../components/Banner.vue';
import BurgerForm from '../components/BurgerForm.vue';

export default{
  name: "Home",
  components: {
    Banner,
    BurgerForm
  }
}


</script>

<style scoped>
  #main-burgerform{
    margin: 50px;
  }
</style>