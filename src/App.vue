<template>
  <div class="wrapper">
    <Documentation />
  </div>
</template>

<script>
import Documentation from "./components/Documentation.vue";
  export default {
    components: { Documentation }
  }
</script>

<style>
  .wrapper {
    font-family: 'Roboto Condensed';
    max-width: 1240px;
    width: 100%;
    margin: 0 auto;
  }
</style>
