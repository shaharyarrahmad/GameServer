<template>
  <img alt="Vue logo" src="./assets/logo.png" />

  <ServerPage msg="Hello" />
</template>

<script>
//import HelloWorldVue from "./components/HelloWorld.vue";
import ServerPage from "./components/ServerPage.vue";
export default {
  name: "App",
  components: {
    // HelloWorld: HelloWorldVue,
    ServerPage: ServerPage,
  },
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
</style>
