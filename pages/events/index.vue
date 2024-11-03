<template>
  <div>hello events</div>
  <input type="text" v-model="id" @keydown="test()" />
  <NuxtLink to="/events/1">push to id</NuxtLink>
</template>

<script lang="ts" setup>
const id = ref("");

function test() {
  console.log(id.value);
}
</script>

<style></style>
