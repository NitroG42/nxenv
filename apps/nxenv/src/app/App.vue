<script setup lang="ts">
  const test = import.meta.env.VITE_TEST_VARIABLE
</script>

<template>
  <div>
    {{ test }}
  </div>
</template>
