<template>
  <div id="app">
    <PDFViewer :url="'/1.pdf'"/>
  </div>
</template>

<script>
import PDFViewer from "../package/index.js";

export default {
  name: 'app',
  components: {
    PDFViewer
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  height: 100vh;
}
body{
  margin: 0;
}
</style>
