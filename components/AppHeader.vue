<script setup>
// Your component logic here
</script>

<template>
  <header class="bg-white shadow">
    <nav class="mx-auto flex gap-6 px-4 py-4 container">
      <NuxtLink
        to="/"
        class="text-gray-700 transition-colors hover:text-blue-600"
      >
        Home
      </NuxtLink>
      <NuxtLink
        to="/about"
        class="text-gray-700 transition-colors hover:text-blue-600"
      >
        About
      </NuxtLink>
    </nav>
  </header>
</template>

<style scoped>
/* Your styles here */
</style>
