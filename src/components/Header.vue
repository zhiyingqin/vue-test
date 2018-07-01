<template>
  <header></header>
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
	z-index: 1;
}
</style>
