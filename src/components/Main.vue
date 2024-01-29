<script setup>
import { ref } from 'vue'
import image1 from "./images/cat.png"

defineProps({
  msg: String,
})

const count = ref(0)
</script>

<template>
  <h1>{{ msg }}</h1>

  <p>
    <b>i like seals and cats 🦭</b>
  </p>
    <p>
    <b>i'm a render artist, texturer, and coder!</b>
    </p>
    <b>kinda fluent in go, lua, vue, and etc</b>

    <h1> my works 🧑‍💻🖼️</h1>
    <img :src="image1" 
    height="432"
    width="768"
    />
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
