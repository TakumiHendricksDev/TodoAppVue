<!-- eslint-disable vue/multi-word-component-names -->
<template>
  <main>
    <span class="border border-indigo-600">
      <p class="text-blue-600">{{ todoName }}</p>
      <input type="checkbox" />
    </span>
  </main>
</template>

<script setup>
import { ref } from "vue";

let todoName = ref("example Todo");
</script>
