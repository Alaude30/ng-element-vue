<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <h1>Angular test on vue</h1>
    <HelloWorld/>
    <app-live-chat domain="default" idx_user="1"></app-live-chat>
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";

export default {
  name: "app",
  components: {
    HelloWorld
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
