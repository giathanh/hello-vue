<template>
  <div class="todo-list">
    <TodoListComponent />
  </div>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";
import TodoListComponent from "@/components/TodoListComponent.vue"; // @ is an alias to /src

@Component({
  components: {
    TodoListComponent
  }
})
export default class TodoList extends Vue {}
</script>
