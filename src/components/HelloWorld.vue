<template>
  <div class="divide-y-2 divide-grey-100">
    <div class="text-3xl">{{ msg }}</div>
    <div class="mt-4">
      <div class="space-y-2" >
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
          <span class="pl-3">count is: <span class="text-indigo-500 font-bold">{{ state.count }}</span></span>
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