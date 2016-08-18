<template>
  <div id="app" class="container">
    <GetTodo></GetTodo>
    <CurrentTodos></CurrentTodos>
  </div>
</template>

<script>
import GetTodo from './components/GetTodo.vue'
import CurrentTodos from './components/CurrentTodos.vue'
export default {
  components: {
    GetTodo,
    CurrentTodos
  }
 
}
</script>

<style>
body {
  font-family: Helvetica, sans-serif;
}
</style>
