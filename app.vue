<template>
  <div>
    <NuxtLayout>
      <NuxtPage />
    </NuxtLayout>
  </div>
</template>

<script setup>
  useHead({
    title: "Nuxt 3 Store",
    link: [
      {rel: "stylesheet", href: "https://fonts.googleapis.com/css2?family=Noto+Sans+JP:wght@100..900&family=Permanent+Marker&display=swap"}
    ]
  })
</script>
