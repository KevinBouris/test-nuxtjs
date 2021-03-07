<template>
  <div class="container bg-gray-800 flex flex-col">
    <nav class="w-2/3 p-8 mb-4 bg-teal-700 flex justify-around text-white">
      <NuxtLink to="/" class="border-gray-700 rounded-3xl p-4">
        Home page
      </NuxtLink>
      <NuxtLink to="/fun" class="border-gray-700 rounded-3xl p-4">
        Fun page
      </NuxtLink>
    </nav>
    <p>Ceci est une phrase drôle</p>
  </div>
</template>

<script>
export default {
  name: 'Fun'
}
</script>

<style scoped>

</style>
