<template>
  <div v-for="todo in todos">
    <p class="todo-item">{{todo.text}} - {{todo.status}}</p>
  </div>
</template>

<script setup lang="ts">
import { todos } from './todo-data';

</script>
