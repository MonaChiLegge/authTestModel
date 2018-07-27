<template>
  <div id="app">
    <LoginView/>
  </div>
</template>

<script>
import LoginView from "./views/LoginView";

export default {
  name: "App",
  components: {
    LoginView
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
