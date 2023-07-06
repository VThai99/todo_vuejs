<script setup lang="ts">
import { RouterLink } from 'vue-router'
</script>
<template>
  <div class="d-flex justify-content-center align-items-center gap-3">
    <RouterLink to="/" class="text-decoration-none">Home Page</RouterLink>
    <RouterLink to="/todo" class="text-decoration-none">Todo List</RouterLink>
  </div>
</template>
