<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />
    <SchoolInfo />
  </div>
</template>

<script>
import SchoolInfo from "./components/SchoolInfo";

export default {
  name: "App",
  components: {
    SchoolInfo,
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
