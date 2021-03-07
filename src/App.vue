<template>
  <div
    class="min-h-screen bg-gray-100 py-6 flex flex-col justify-center sm:py-12"
  >
    <div>
    <h1 class="text-3xl text-blue-400">Hello, Tailwind!</h1>
    <p class="my-3">Let's learn how to use this new CSS framework.</p>
    </div>
    <div class="relative px-4 py-10 bg-white shadow-lg sm:rounded-3xl sm:p-20">
      <div class="relative py-3 sm:max-w-xl sm:mx-auto">
        <img alt="Vue logo" src="./assets/logo.png" class="mx-auto" />
        <HelloWorld msg="vite-04 : Vue 3 + tailwind.css + Vite   " />
        <p class="ml-2 text-pink-400">Testing vue3 + Tailwind.css</p>
      </div>
    </div>
  </div>
</template>

<script setup>
import HelloWorld from "./components/HelloWorld.vue";

// This starter template is using Vue 3 experimental <script setup> SFCs
// Check out https://github.com/vuejs/rfcs/blob/script-setup-2/active-rfcs/0000-script-setup.md
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>