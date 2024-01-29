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

    <h1>my socials 📱</h1>
      <p><b>discord: naymmmiscool_</b></p>
      <p><b>twitter: @naymmm_</b></p>
      <p><b>bluesky: @naym.bsky.social</b></p>
      <p><b>youtube: @naymmm_</b></p>
      <p><b>email: naymmm@murder.academy</b></p>

    <h3>contact me through email or discord! i'm not active on twitter</h3>
    <h3>i do texturing and rendering commissions! dm me on discord</h3>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
