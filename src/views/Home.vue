<template>
  <div>
    <div class="home">
      <Navbar />
    </div>

    <div>
      <b-jumbotron class="jumbotron" text-variant="white" border-variant="dark">
        
        <template #header>We play with words. Words are our games.</template>
        <template #lead>Download our datasets and publications? Sign In or Sign Up now!</template>
      </b-jumbotron>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import Navbar from "@/components/Navbar.vue";

export default {
  name: "Home",
  components: {
    Navbar,
  },
};
</script>
