<template>
  <div class="divide-y-2 divide-grey-100 space-y-4">
    <div class="text-3xl">{{ msg }}</div>
    <div class="mt-4">
      <div class="space-y-2">
        <div class="mt-4">
          <p>
            <a href="https://vitejs.dev/guide/features.html" target="_blank"
              >Vite Documentation</a
            >
            |
            <a href="https://v3.vuejs.org/" target="_blank"
              >Vue 3 Documentation</a
            >
          </p>
        </div>
        <div>
          <button
            class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 border border-blue-700 rounded"
            @click="state.count++"
          >
            Button
          </button>
          <span class="pl-3"
            >count is:
            <span class="text-indigo-500 font-bold">{{
              state.count
            }}</span></span
          >
        </div>
        <div>
          <p>
            Edit
            <code>components/HelloWorld.vue</code> to test hot module
            replacement.
          </p>
        </div>
      </div>
    </div>
    <div class="mt-4">
      <div class="my-4">
        <h1 class="text-green-600 text-5xl font-bold">GeeksforGeeks</h1>
        <b>Tailwind CSS Height Class</b>
        <div
          class="flex flex-wrap-reverse p-4 mx-5 space-x-2 h-64 bg-green-200"
        >
          <div class="h-8 w-10 md:w-14 bg-green-400 rounded-lg">h-8</div>
          <div class="h-12 w-10 md:w-14 bg-green-400 rounded-lg">h-12</div>
          <div class="h-16 w-10 md:w-14 bg-green-400 rounded-lg">h-16</div>
          <div class="h-20 w-10 md:w-14 bg-green-400 rounded-lg">h-20</div>
          <div class="h-24 w-10 md:w-14 bg-green-400 rounded-lg">h-24</div>
          <div class="h-32 w-10 md:w-14 bg-green-400 rounded-lg">h-32</div>
          <div class="h-40 w-10 md:w-14 bg-green-400 rounded-lg">h-40</div>
          <div class="h-48 w-10 md:w-14 bg-green-400 rounded-lg">h-48</div>
        </div>
      </div>
    </div>
    <div>
      <div class="mt-4">
        <b>Tailwind CSS Height Class</b>
        <div class="mx-4 h-48 bg-green-200 p-8">
          <div class="h-full bg-green-400 rounded-lg">h-full</div>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
import { defineProps, reactive } from "vue";

defineProps({
  msg: String,
});

const state = reactive({ count: 0 });
</script>

<style scoped>
a {
  color: #42b983;
}
</style>