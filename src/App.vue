<script setup>
import TodoList from './components/TodoList.vue'
</script>

<template>
  <div id ="app" class="container">
      <TodoList />
    </div>

</template>

<style>
#app {
  font-size: 24px;
}
.container {
  max-width: 600px;
  margin: 0 auto;
}
</style>
