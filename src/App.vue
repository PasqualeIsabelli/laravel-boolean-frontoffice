<script>
  import TheHeader from './components/TheHeader.vue';
  import TheFooter from './components/TheFooter.vue';
  import Slider from './components/Slider.vue';

  export default{
    components: {
      TheHeader,
      TheFooter,
      Slider,
    }
  }
</script>

<template>
  <TheHeader></TheHeader>

  <main>
    <Slider></Slider>
    <router-view></router-view>
  </main>
  
  <TheFooter></TheFooter>
</template>

<style lang="scss">


</style>
