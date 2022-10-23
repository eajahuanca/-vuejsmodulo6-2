<template>
	<NavbarMenu />
	<main>
		<Practica2 />
	</main>
	<FooterMenu />
</template>

<script>
import Navbarmenu from "./components/Navbarmenu.vue";
import Practica2 from './components/Practica2.vue'
import Footermenu from "./components/Footermenu.vue";

export default {
	name: 'App',
	components: {
		Navbarmenu,
		Practica2,
		Footermenu
	}
}
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

.color-box {
	width: 40px;
	height: 40px;
	border-radius: 50%;
	margin: 7px;
	display: inline-block;
}

.clic {
	cursor: pointer;
}

.quantity button {
	border-radius: 50%;
	display: inline-block;
	width: 30px;
}

.quantity div {
	text-align: center;
	min-width: 30px;
	display: inline-block;
	font-weight: bold;
}

.buy-box {
	margin: 20px;
}

footer {
	text-align: center;
	padding: 30px 10px;
	margin-top: 50px;
	min-height: 100px;
}

.container {
	margin-top: 50px;
}

.producto-relacionado-precio {
	background: orangered;
	color: white;
	text-align: center;
	padding: 10px;
}
</style>
