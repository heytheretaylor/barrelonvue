<template>
  	<div class="signin">
	  	<form novalidate @submit.stop.prevent="submit">
			<md-input-container>
    			<label>Username</label>
    			<md-textarea></md-textarea>
			</md-input-container>
			<md-input-container md-has-password>
    			<label>Password</label>
    			<md-input type="password"></md-input>
			</md-input-container>
			<md-button class="md-raised md-primary">Submit</md-button>

		</form>
	</div>
</template>

<script>
export default {
  name: 'signin',
  data () {
    return {
      msg: 'Please Login'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}
</style>
