<template>
  <div class="min-h-screen bg-gradient-to-br from-blue-100 via-white to-purple-100 flex flex-col items-center justify-center px-6">
    <div class="max-w-2xl text-center">
      <h1 class="text-5xl font-extrabold text-gray-800 leading-tight mb-4">
        Welcome to <span class="text-purple-600">Nuxt Starter</span>
      </h1>
      <p class="text-lg text-gray-600 mb-8">
        This starter template is built with Nuxt 3 and Tailwind CSS to help you launch fast with a clean, modern UI.
      </p>
      <div class="flex flex-col sm:flex-row gap-4 justify-center">
        <NuxtLink to="/about" class="px-6 py-3 bg-purple-600 text-white rounded-xl text-lg font-medium shadow-md hover:bg-purple-700 transition">
          About Us
        </NuxtLink>
        <NuxtLink to="/resume" class="px-6 py-3 bg-white border border-purple-600 text-purple-700 rounded-xl text-lg font-medium shadow-md hover:bg-purple-100 transition">
          Resume
        </NuxtLink>
      </div>
    </div>

    <footer class="mt-16 text-sm text-gray-500">
      © {{ new Date().getFullYear() }} Nuxt Starter. Built by you.
    </footer>
  </div>
</template>

<script setup>
// No script needed
</script>
