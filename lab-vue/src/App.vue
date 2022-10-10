<template>
	<div>APP</div>

	<Home />
	<About />
	<Texto />
	<p>{{ newText }}</p>
	<Buttons />
</template>

<script setup>
import { ref } from "vue";
import Texto from "./components/Texto.vue";
import Buttons from "./components/Buttons.vue";
import Home from "./components/Home.vue";
import About from "./components/About.vue";

let newText = "texto desde javascript";
</script>

<style scoped></style>
