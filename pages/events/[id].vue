<template>
  <div>event id: {{ $route.params.id }}</div>
  <div>event id: {{ id }}</div>
</template>

<script lang="ts" setup>
const nuxt = useNuxtApp();
const route = useRoute();
const id = route.params.id;
</script>

<style></style>
