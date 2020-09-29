<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" msg2="Hello Papa" />
    <HelloPapa msg="Hello Papa" />
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import HelloPapa from "./components/HelloPapa.vue";

export default {
  name: "App",
  components: {
    HelloWorld,
    HelloPapa,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #0d09f9;
  margin-top: 60px;
}
</style>
