<script setup>
import '@unocss/reset/tailwind-compat.css'

useHead({
  htmlAttrs: {
    lang: 'en',
  },
  charset: 'utf-8',
  title: '',
  titleTemplate: title => title !== '' ? `${title} · ` : title,
  meta: [
    { name: 'description', content: '' },
    { property: 'og:image', content: '' },
    { name: 'twitter:card', content: '' },
    { name: 'twitter:site', content: '' },
    { name: 'twitter:creator', content: '' },
  ],
  link: [
    {
      rel: 'icon', type: 'image/webp', href: '',
    },
  ],
})
</script>

<template>
  <NuxtLayout>
    <NuxtLoadingIndicator />
    <NuxtPage />
  </NuxtLayout>
</template>

<style>
html,
body,
#__nuxt {
  height: 100vh;
  margin: 0;
  padding: 0;
  background: ;
  color: ;
  color-scheme: dark;
}
</style>
