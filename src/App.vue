<template>
  <Homepage />
</template>

<script>
import Homepage from "./pages/Homepage.vue";

export default {
  name: "App",
  pages: {
    Homepage,
  },
};
</script>

<style scoped>
body {
  width: 100%;
}
</style>