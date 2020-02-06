<template>
  <div>
    <Toolbar></Toolbar>
    <Bod></Bod>
    <Footer></Footer>
  </div>
</template>

<script>
import Toolbar from "./components/Toolbar.vue";
import Footer from "./components/Footer.vue";
import Bod from "./components/Bod.vue";

export default {
  components: {
    Toolbar,
    Footer,
    Bod
  },
  data() {
    return {};
  }
};
</script>

<style>
</style>