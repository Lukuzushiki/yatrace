<template>
  <div id="app">
    <Navbar />
  </div>
</template>

<script>
import "bootstrap/dist/css/bootstrap.css";
import Navbar from "@/components/Navbar.vue";

export default {
  components: {
    Navbar
  }
};
</script>

<style>
#nav a.router-link-exact-active {
  color: #42b983;
}

.logo {
  width: 190px;
  height: 60px;
}
</style>
