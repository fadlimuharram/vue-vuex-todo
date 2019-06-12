<template>
  <div>
    Filter Todo:
    <select @change="filterTodos($event)">
      <option value="200">200</option>
      <option value="100">100</option>
      <option value="50">50</option>
      <option value="10">10</option>
    </select>
  </div>
</template>

<script>
import { mapActions } from "vuex";
export default {
  name: "Filter Todo",
  methods: {
    ...mapActions(["filterTodos"])
  }
};
</script>

<style>
</style>
