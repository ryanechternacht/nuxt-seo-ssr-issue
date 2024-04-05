<template>
  <div>i'm not a real page, just a redirect</div>
</template>

<script setup>
// gets thrown away cuz of the redirect
useServerSeoMeta({
  title: 'redirect page',
  ogTitle: 'redirect page',
  description: 'redirect description',
  ogDescription: 'redirect description',
  // ogImage: ,
})

await navigateTo('/')
</script>