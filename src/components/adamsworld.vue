<script setup>
import { ref } from 'vue'

defineProps({
  msg: String,
})

const count = ref(0)
</script>

<template>
  <h1>{{ msg }}</h1>

  <div class="card">
    <button type="button" @click="count++">count is {{ count }}</button>
    <p>
      Edit
      <code>components/adamsworld.vue</code> to test.  Low-code Web 3.0 Docker application developed for scalability and seamlessness.  This is a dockerized turn-key Web Application backwards compatible with Web 1.0 - Web 3.0 W3C cloud-based technologies.  
       <h2>Stay current and secure. </h2>
      This out of the box AI is scalable with cutting-edge framework, mitigating the need to overhaul and modernize business processes as W3C Web standards evolve.
    </p>
  </div>

  <p>
    Check out
    <a href="https://vuejs.org/guide/quick-start.html#local" target="_blank"
      >create-vue</a
    >, the official Vue + Vite starter
  </p>
  <p>
    Install
    <a href="https://github.com/vuejs/language-tools" target="_blank">Vue IDE Language Tools</a>
    for best user experience.
  </p>
  <p class="read-the-docs">Click on the Vite and Vue logos to learn about this framework.</p>
  <br>
  <div><p>Copyright 2023 URM Stores by Adam Morien</p>
All rights reserved.</div>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
