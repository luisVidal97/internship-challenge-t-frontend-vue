<template>
  <div id="app">
    <NavBar />
    <b-container>
      <router-view />
    </b-container>
  </div>
</template>

<script>
import NavBar from "./components/NavBar";

export default {
  components: {
    NavBar
  }
};
</script>

<style></style>
