<template>
  <main class="flex bg-gray-200 h-screen p-5 justify-center">
    <div class="profile shadow p-5 m-auto rounded-lg">MyProfile {{ name }}</div>
  </main>
</template>

<script setup>
import { ref } from 'vue'
const name = ref('konlatee')
</script>

<style>
.profile {
  background-color: white;
}
</style>
