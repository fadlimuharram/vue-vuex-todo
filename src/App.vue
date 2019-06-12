<template>
  <div id="app">
    <div class="container">
      <AddTodo/>
      <FilterTodo/>
      <Todos/>
    </div>
  </div>
</template>

<script>
import Todos from "./components/Todos.vue";
import AddTodo from "./components/AddTodo";
import FilterTodo from "./components/FilterTodo";

export default {
  name: "app",
  components: {
    FilterTodo,
    Todos,
    AddTodo
  }
};
</script>

<style>
body {
  line-height: 1.6;
  background: #e8f7f0;
}

.container {
  max-width: 1100px;
  margin: auto;
  overflow: auto;
  padding: 0 2rem;
}
</style>
