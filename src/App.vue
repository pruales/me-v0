<template>
  <div id="app">
    <Home/>
  </div>
</template>

<script>
import Home from './components/Home';
export default {
  name: 'app',
  components: {
    Home
  }
}
</script>

<style>
@import url("https://use.typekit.net/bjk4etu.css");
@import url('https://fonts.googleapis.com/css?family=Space+Mono:400,400i,700,700i&display=swap');
#app {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  display: flex;
  align-items: center;
  justify-content: center;
  height: 100vh;
}

body{
  background-color: #111517;
  }
</style>
