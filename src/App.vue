<template>
	<div id="app">
		<Header/>
	</div>
</template>

<script>
import Header from './components/Header'
import 'vuetify/dist/vuetify.min.css'

export default {
	name: 'app',
	components: {
		Header
	}
}
</script>

<style lang="scss">

$sidebar-default: #3c3c3c;
$content-default: #515151;

html,body {
	margin:0;
}

#app {
	font-family: Tahoma, 'Segoe UI', Geneva, Verdana, sans-serif;
	-webkit-font-smoothing: antialiased;
	-moz-osx-font-smoothing: grayscale;
	background-color: green;
	width: 100%;
	height: 100vh;
}

</style>
