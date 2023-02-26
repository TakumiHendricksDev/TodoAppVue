<!-- eslint-disable vue/multi-word-component-names -->
<template>
  <main>
    <CreateTodo></CreateTodo>
    <TodoList></TodoList>
  </main>
</template>

<script setup lang="ts">
import CreateTodo from "@/components/CreateTodo.vue";
import TodoList from "@/components/TodoList.vue";
</script>
