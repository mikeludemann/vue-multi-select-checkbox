<template>
	<div class="home">
		<img alt="Vue logo" src="../assets/logo.png">
		<HelloWorld msg="Welcome to Your Vue.js App"/>
		<checkbox />
	</div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue';
import checkbox from '@/components/checkbox.vue';

export default {
	name: 'Home',
	components: {
		HelloWorld,
		checkbox
	}
}
</script>
