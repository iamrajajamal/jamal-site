<template>
  <div class="home main-content">
    <div class="left-content">
      <h1>Crypto LOGO</h1>
      <p class="subtxt">Description blah blah blah</p>
      <p class="subtxt">Skills and Experience blah blah blah</p>
      <router-link to="/portfolio/two"><img src="../assets/arrow-down.svg" class="arrow arrow-down"></router-link>
    </div>
    <div class="right-content img2">
      <img src="../assets/logo.svg">
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "one",
  components: {
    HelloWorld
  }
};
</script>

<style lang="scss" scoped>

$page_color: #615B7E;

h1 {
  color: $page_color !important;
}

.img2 {
  background: $page_color;

  img {
    width: 50%;
  }
}


</style>