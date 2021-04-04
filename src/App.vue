<template>
  <div id="app">
    <appHeader msg="Public apis" />
    <appBody /> 
    <h4>Built by <a href="http://twitter.com/bethropolis">Bethropolis</a></h4>
  </div>
</template>

<script>
import appHeader from "./components/header";
import appBody from "./components/api";
export default {
  name: "App",
  components: {
    appHeader,
    appBody,
  },
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
a{
  color: #6EE7B7; 
}
</style>
