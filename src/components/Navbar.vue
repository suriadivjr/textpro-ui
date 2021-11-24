<template>
  <div>
    <b-navbar type="light" variant="light" class="navbar">
      <b-navbar-nav>
        <b-nav-item href="#">LOGO TEXTPRO</b-nav-item>
      </b-navbar-nav>

      <div class="collapse navbar-collapse justify-content-end">
        <b-navbar-nav>
            <b-nav-item href="#">HOME</b-nav-item>
            <b-nav-item href="#">DATASETS</b-nav-item>
            <b-nav-item href="#">PROJECTS</b-nav-item>
            <b-nav-item href="#">PUBLICATIONS</b-nav-item>
            <b-nav-item href="#">LOG IN</b-nav-item>
        </b-navbar-nav>
      </div>
    </b-navbar>
  </div>
</template>

<script>
export default {
  name: "Navbar",
};
</script>

<style>
.navbar.navbar-light.bg-light {
  background-color: #00dad3 !important;
}
</style>