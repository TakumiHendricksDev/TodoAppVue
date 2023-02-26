<template>
  <main>
    <hr class="rounded" />
    <ul>
      <li>
        <Todo></Todo>
      </li>
    </ul>
  </main>
</template>

<script setup lang="ts">
import { ref } from "vue";
import Todo from "@/components/Todo.vue";

let sentence = ref("Hey There!");
</script>
