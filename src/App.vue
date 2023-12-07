<script setup lang="ts">
const envVars = import.meta.env || {};
</script>

<template>
	<div>
		<div v-for="(key, index) in Object.keys(envVars)" :key="index">
			{{ `${key}: ${envVars[key]}` }}
		</div>
	</div>
</template>

<style scoped>
.logo {
	height: 6em;
	padding: 1.5em;
	will-change: filter;
	transition: filter 300ms;
}
.logo:hover {
	filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
	filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
