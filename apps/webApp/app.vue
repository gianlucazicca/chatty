<script setup lang="ts">
const { data: test } = await useAsyncData('test', () => $fetch('http://localhost:3001/'), 'GET');
console.log(test);
</script>

<template>
  <div>
    <NuxtWelcome />
    <div class="" />
  </div>
</template>
