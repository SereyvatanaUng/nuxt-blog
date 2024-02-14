<template>
  <div>This is blog page.{{ route.params.id }}</div>
</template>

<script setup>
const route = useRoute();
</script>
