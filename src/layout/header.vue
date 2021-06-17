<template>
  <nav class="navbar navbar-dark bg-primary">
    <a href="#" class="navbar-brand">
      <img src="../assets/logo-white.png" alt="Logo" width="30" height="30" />
    </a>
    <span class="navbar-text text-white"> {{ title }} </span>
  </nav>
</template>

<script>
export default {
  name: "Header",
  props: ["title"],
};
</script>

<style>
</style>