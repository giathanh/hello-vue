<template>
  <div class="hello">
    <ul>
      <li>Todo A</li>
      <li>Todo B</li>
    </ul>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";

@Component
export default class TodoListComponent extends Vue {}
</script>
