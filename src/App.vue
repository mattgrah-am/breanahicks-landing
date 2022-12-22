<template>
  <div class="grid h-screen place-content-center text-center text-purple-900">
    <h1 class="heading border-t border-purple-900 px-4 pt-4 text-3xl font-bold">
      Breana Hicks
    </h1>
    <p class="text-lg">Nails and Crafts</p>
    <a
      href="mailto&#58;h%65llo%40&#98;%7&#50;ea&#110;ahicks&#46;c%6F%6D?subject=Message from Breanahicks.com website"
      class="flex justify-center border-b border-purple-900 pb-4"
    >
      <button
        type="button"
        class="mt-4 flex items-center gap-2 rounded-full bg-purple-900 px-3 py-1.5 text-center text-sm text-white hover:bg-purple-800 focus:outline-none focus:ring-4 focus:ring-purple-300 dark:hover:bg-purple-700"
      >
        <IconEmail class="h-4 w-4" />
        Contact
      </button>
    </a>
  </div>
</template>

<script setup lang="ts">
import IconEmail from "./components/IconEmail.vue";
</script>
