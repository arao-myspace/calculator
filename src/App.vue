<template>
  <div id="app">
    <Calculator></Calculator>
  </div>
</template>

<script>
import Calculator from "./components/Calculator.vue";

export default {
  name: "App",
  components: {
    Calculator,
  },
};
</script>

<style>
#app {
  display: flex;
  align-content: center;
  align-items: center;
  width: 95%;
  height: 100vh;
  margin: auto;
}
body {
  height: 100%;
}
</style>
