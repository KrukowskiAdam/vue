
<script setup lang="ts">
import { useRouter } from 'vue-router';
const route = useRouter()

</script>

<template>
  <div>
    <h1>Projects Name {{ $route.params?.id }}</h1>
  </div>
</template>
