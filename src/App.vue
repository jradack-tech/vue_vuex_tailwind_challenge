<template>
  <div id="app">
    
    <Introduction></Introduction>
  </div>
</template>

<script>
import Introduction from "./components/Introduction.vue";

export default {
  name: "app",
  components: {
    Introduction
  }
};
</script>

<style>
body {
  @apply font-sans antialiased bg-gray-200;
}
</style>
