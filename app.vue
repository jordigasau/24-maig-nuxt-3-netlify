<template>
  <div>
    <NuxtWelcome />
  </div>
</template>

<script setup >

let image = "la imagen"

useHead({
  title: 'My App',
  meta: [
    { name: 'description', content: 'My amazing site.' },
    //<meta property=”og:image” content=”enlace al archive de la imagen” />
    {name:"og:image",content:image}
  ],
})
</script>