<template>
  <div id="app">
		<router-view />
  </div>
</template>

<script>
export default {
  name: 'App',
	mounted() {
		// console.log(process.env.VUE_APP_WEATHER_KEY)
	},
}
</script>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

/* #app {
  background-image: url("./assets/cold-bg.jpg");
  background-size: cover;
  background-position: 50%;
  transition: 0.5s;
}

#app.warm {
  background-image: url("./assets/warm-bg.jpg");
} */
</style>
