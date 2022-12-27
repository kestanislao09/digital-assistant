<template>
  <TodoList :todos="todos"/>
</template>

<script setup>
import { todos } from '@/assets/todos.js'
import TodoList from '@/components/TodoList.vue'
</script>

<style>
</style>
