<template>
  <div>Welcome home page.</div>
</template>

<script setup>
useSeoMeta({
  title: "Main Page",
  ogTitle: "This is the main page",
  description: "This is my amazing site, let me tell you all about it.",
  ogDescription: "This is my amazing site, let me tell you all about it.",
  ogImage: "https://example.com/image.png",
  twitterCard: "summary_large_image",
});

useHead({
  htmlAttrs: { lang: "en" },
  link: [
    {
      rel: "icon",
      type: "image/png",
      href: "favicon.png",
    },
  ],
});
</script>
