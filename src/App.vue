<template>
  <div class="wrapper">
    <Header/>
    <div class="wrapper-content">
      <div class="container">
        <router-view/>
      </div>
    </div>
    <Footer/>
  </div>
</template>

<script>
import Header from "@/components/Header-main.vue";
import Footer from "@/components/Footer-main.vue";

export default {
  components: {
    Header,
    Footer,
  },
};
</script>

<style lang="scss">
</style>
