<template>
  <header>
  	<a href="" class="logo">
  		<img src="../assets/logo.png"/>
  		<span>vue-test</span>
  	</a>
  </header>
</template>

<script>
export default {
  name: 'Header',
  data () {
    return {
      msg: 'Welcome to my project'
    }
  }
}
</script>
<style scoped>
header {
	width: 100%;
	height: 60px;
	border: 1px solid lightgray;
	position: fixed;
	top: 0;
	line-height: 60px;
	/*z-index: 1;*/
	/*opacity: 0.5;*/
}
a {
	text-decoration: none;
}
.log {
	display: inline-block;
	height: 40px;
}
.logo img {
   width: 40px;
   height: 40px;
}
</style>
