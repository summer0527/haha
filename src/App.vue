<template>
  <div id="app">
  	<div class="dell" @click="handleClick">{{message}}</div>
  </div>
</template>

<script>
export default {
  name: 'App',
  data () {
  	return{
  		message:'我是小仙女'
  	}
  },
  methods:{
  	handleClick () {
  		this.message='才怪'
  	}
  }
}
</script>

<style scoped>
	.dell{
		color:red;
	}
</style>
