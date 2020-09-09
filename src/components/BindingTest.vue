<template>
  <div>
	<p>
		BindingTest:{{msg}}
	</p>
	<input type="text" v-model="msg">
  </div>
</template>

<script>
export default {
  name: 'BindingTest',
  data() {
	return {
		msg:''
	}
  }
}
</script>
