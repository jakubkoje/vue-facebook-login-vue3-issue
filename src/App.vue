<template>
	<img alt="Vue logo" src="./assets/logo.png" />
	<HelloWorld msg="Welcome to Your Vue.js App" />
	<VFacebookLogin app-id="966242223397117" />
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';
import VFacebookLogin from 'vue-facebook-login-component';

export default {
	name: 'App',
	components: {
		HelloWorld,
		VFacebookLogin,
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
