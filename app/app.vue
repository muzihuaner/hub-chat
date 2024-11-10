<template>
  <NuxtRouteAnnouncer />
  <NuxtLoadingIndicator />
  <NuxtPage />
</template>

<script setup lang="ts">
useHead({
  bodyAttrs: {
    class: 'bg-white dark:bg-gray-900',
  },
});
useSeoMeta({
  title: '快点AI助手',
  ogTitle: '快点AI助手 - Cloudflare AI LLM 模型平台',
  description:
    '快点AI助手是一个 Cloudflare Workers AI LLM 模型平台 使用 NuxtHub 和 Nuxt UI构建.',
  ogImage:
    'https://assets.hub.nuxt.com/eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJ1cmwiOiJodHRwczovL2h1Yi1jaGF0Lm51eHQuZGV2IiwiaWF0IjoxNzI0NTcyMzI3fQ.HqgnQrHVs34qdjFSP6RYy_M94duSAgPEvGgHF5j0xvI.jpg?theme=light',
  twitterCard: 'summary_large_image',
});
</script>
