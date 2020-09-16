<template>
  <div class="home">
    <TodoList msg="Welcome to Your Vue.js App" />
  </div>
</template>

<script>
import TodoList from "@/components/TodoList.vue";

export default {
  name: "Home",
  components: {
    TodoList
  }
};
</script>
