<template>
  <div id="app">
    <!-- <HelloWorld msg="Welcome to Your Vue.js App" /> -->
    <mainTitle msg="La mia prima app con Vue CLI!" />
    <heroJumbotron />
  </div>
</template>

<script>
// import HelloWorld from "./components/HelloWorld.vue";
import mainTitle from "./components/mainTitle.vue";
import heroJumbotron from "./components/heroJumbotron.vue";
export default {
  name: "App",
  components: {
    // HelloWorld,
    mainTitle,
    heroJumbotron,
  },
};
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
