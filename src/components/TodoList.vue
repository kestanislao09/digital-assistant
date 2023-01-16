<template>
  <ul>
    <li v-for="todo in todos" :key="todo.title">
      <h1>{{ todo.title }}</h1>
      <p>{{ todo.description }}</p>
    </li>
  </ul>
</template>

<script setup>
defineProps({
  todos: Array,
})
</script>

<style lang="scss" scoped>

</style>
