<script setup lang="ts">
import navigation from './components/navigation.vue';
import { routerLink, routerView } from 'vue-router';
</script>

<template>
  <navigation />
  <RouterView />
</template>

<style scoped></style>
