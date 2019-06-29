<template>
  <div id="app">
    <Home/>
    <Footer/>
  </div>
</template>

<script>
import Home from './components/Home';
import Footer from './components/Footer';

export default {
  name: 'app',
  components: {
    Home,
    Footer
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

a {
	text-decoration: none;
	color: aquamarine;
}

a:-webkit-any-link {
	text-decoration: none;
	cursor: pointer;
}
</style>
