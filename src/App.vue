<script setup>
import TodoApp from './components/TodoApp.vue'
</script>

<template>
  <RouterView />

  <TodoApp />
</template>

<style>
* {
  margin: 0;
  padding: 0;
}
#app {
  background-color: #597d9a;
  display: flex;
  justify-content: center;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
