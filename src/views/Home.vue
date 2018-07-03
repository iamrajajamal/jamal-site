<template>
  <div class="home main-content">
    <div class="left-content">
      <h1>2 years of Programming Experience</h1>
      <p class="subtxt">Description blah blah blah</p>
      <p class="subtxt">Skills and Experience blah blah blah</p>
    </div>
    <div class="right-content img1">
      <button> <router-link to="/portfolio/one">Browse Work</router-link> </button>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "home",
  components: {
    HelloWorld
  }
};
</script>

<style scoped>
.img1 {
  background: url('../assets/home.jpg');
}
</style>