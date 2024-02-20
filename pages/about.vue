<template>
  <div>This is about page.</div>
  <div>
    <button @click="enableCustomLayout">Update layout</button>
  </div>
</template>

<script setup>
function enableCustomLayout() {
  setPageLayout("another");
}

useHead({ title: "About" });
</script>
