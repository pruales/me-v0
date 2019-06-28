<template>
  <div class="portfolio">
    <a href=""><h1>ICYMT</h1></a>
		<a href=""><h1>OMNILIFE</h1></a>
		<a href=""><h1>THE SIDE PROJECT</h1></a>
  </div>
</template>

<script>
export default {
  name: "Home",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.portfolio {
  font-family: monotype-grotesque-display-c, sans-serif;
  font-weight: 700;
	font-style: normal;
	font-size: 25px;
	
}

.portfolio a {
	text-decoration: none;
	color: aquamarine;
}

a:-webkit-any-link {
	text-decoration: none;
	cursor: pointer;
}

</style>
