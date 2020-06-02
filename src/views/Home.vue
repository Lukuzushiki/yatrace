<template>
  <div>
    <Jumbotron />
    <div class="container">
      <h2>Best Seller</h2>
      <p>The favourite cake only for you</p>
      <div class="row">
        <div class="col"></div>
      </div>
    </div>
  </div>
</template>

<script>
import Jumbotron from "../components/Jumbotron.vue";

export default {
  name: "Home",
  components: {
    Jumbotron
  }
};
</script>
