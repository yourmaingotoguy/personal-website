<script setup>
import { RouterView } from "vue-router";
import TopNavigation from "./components/TopNavigation.vue";
</script>

<template>
  <div class="container mx-auto">
    <top-navigation />
    <RouterView />
  </div>
</template>

<style scoped></style>
