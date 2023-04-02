<template>
  <h1 class="toDoList">TO-DO LIST</h1>
<componenteTodoList></componenteTodoList>
<componenteTodoForm></componenteTodoForm>
<div class="allNotes">
    <ul class="noteList">
        aqui va una nota
    </ul>
    <button class="doneNote">Done</button>
    <button class="removeNote">Remove</button>
</div>
</template>

<script setup lang="ts">
import componenteTodoList from './components/todo-list.vue';
import componenteTodoForm from './components/todo-form.vue';
</script>