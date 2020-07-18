<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.svg" />
    <HelloWorld msg="Welcome to vuejjjjj." />
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";

export default {
  name: "App",
  components: {
    HelloWorld
  }
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

#app img {
  height: 200px;
  width: 200px;
}
</style>
