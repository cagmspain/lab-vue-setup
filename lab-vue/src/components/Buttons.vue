<template>
	<button @click="helloWorld()">Click me!</button>
</template>

<script setup>
const helloWorld = () => {
	alert("Hello world!!");
};
</script>

<style scoped></style>
