<script setup lang="ts">
import { useRoute } from "nuxt/app";

const route = useRoute()
</script>

<template>
  <div>
    <h1>Nuxt Routing set up successfully!</h1>
    <p>Current route: {{ route.path }}</p>
    <a href="https://nuxt.com/docs/getting-started/routing" target="_blank">Learn more about Nuxt Routing</a>
  </div>
  <h1 class="text-3xl font-bold underline">
    Hello world!
  </h1>
</template>
