<template>
  <div class="min-h-screen bg-gradient-to-br from-blue-100 via-white to-purple-100 flex items-center justify-center px-6 py-12">
    <div class="max-w-3xl w-full bg-white p-8 rounded-2xl shadow-xl">
      <h1 class="text-4xl font-bold text-purple-700 mb-4 text-center">My Resume</h1>

      <div class="text-center mb-6">
        <p class="text-lg text-gray-700">👋 Hi! I'm a passionate and experienced</p>
        <h2 class="text-2xl font-semibold text-purple-600 mt-2">Full-Stack Developer</h2>
        <p class="text-gray-600 mt-1">
          with expertise in AI, Mobile, Web, Blockchain, and Desktop Applications.
        </p>
      </div>

      <div class="grid sm:grid-cols-2 gap-6 mt-6">
        <div>
          <h3 class="text-xl font-semibold text-purple-600 mb-2">💻 Web Development</h3>
          <ul class="text-gray-700 list-disc list-inside space-y-1">
            <li>Nuxt.js / Vue.js / React</li>
            <li>Node.js / Express / REST API</li>
            <li>Tailwind CSS / UI Design</li>
            <li>Next.js / Firebase / SSR</li>
          </ul>
        </div>

        <div>
          <h3 class="text-xl font-semibold text-purple-600 mb-2">📱 Mobile Development</h3>
          <ul class="text-gray-700 list-disc list-inside space-y-1">
            <li>Flutter / Dart</li>
            <li>React Native</li>
            <li>Firebase Auth & Notifications</li>
            <li>Camera / AI / OCR / TCP Client</li>
          </ul>
        </div>

        <div>
          <h3 class="text-xl font-semibold text-purple-600 mb-2">🧠 AI / Machine Learning</h3>
          <ul class="text-gray-700 list-disc list-inside space-y-1">
            <li>Python / TensorFlow / PyTorch</li>
            <li>FastAPI + Model Deployment</li>
            <li>Computer Vision (CV)</li>
            <li>Edge AI (e.g. Hailo-8, Raspberry Pi)</li>
          </ul>
        </div>

        <div>
          <h3 class="text-xl font-semibold text-purple-600 mb-2">⛓️ Blockchain</h3>
          <ul class="text-gray-700 list-disc list-inside space-y-1">
            <li>Solidity / Smart Contracts</li>
            <li>DApp Frontend Integration</li>
            <li>Web3.js / Ethers.js</li>
            <li>Tokenomics / GameFi / DAO</li>
          </ul>
        </div>

        <div>
          <h3 class="text-xl font-semibold text-purple-600 mb-2">🖥️ Desktop App Development</h3>
          <ul class="text-gray-700 list-disc list-inside space-y-1">
            <li>Electron.js / Tauri / NW.js</li>
            <li>Python Tkinter / PyQt / wxPython</li>
            <li>Cross-platform packaging (Windows, macOS, Linux)</li>
            <li>Local storage, IPC, serial and file system access</li>
          </ul>
        </div>
      </div>

      <div class="mt-10 text-center">
        <NuxtLink to="/" class="text-purple-600 hover:underline font-medium">
          ← Back to Home
        </NuxtLink>
      </div>
    </div>
  </div>
</template>

<script setup>
// This is a static profile/resume page with Desktop App section
</script>
