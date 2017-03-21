<template>
	<div id="app">
		<Signin></Signin>
		<md-menu>
			<md-button md-menu-trigger>Bottom Right</md-button>
			<md-menu-content>
				<md-menu-item>My Item 1</md-menu-item>
				<md-menu-item>My Item 2</md-menu-item>
				<md-menu-item>My Item 3</md-menu-item>
			</md-menu-content>
		</md-menu>
	</div>
</template>

<script>
import Signin from './components/Signin'
import VueMaterial from 'vue-material'

export default {
  name: 'app',
  components: {
    Signin, VueMaterial
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
  margin-top: 60px;
}
</style>
