<template>
  <div id="app">
    <img src="./assets/LOGO-SLOGAN-ING-18-1536x702.png" alt="Sefar" style="width: 200px; margin-top: 15px">
    <h3>Ejemplo PDF en Vue</h3>
    <WebViewer
      initialDoc="https://sefarlibrary.netlify.app/familias.pdf"
    />
  </div>
</template>

<script>
import WebViewer from "./components/WebViewer.vue";

export default {
  name: "App",
  components: {
    WebViewer,
  },
};
</script>

<style>
html,
body {
  margin: 0;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin: 0 auto;
}
</style>
