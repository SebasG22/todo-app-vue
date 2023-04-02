<template>
    <input type="text" placeholder="write your note" v-model="inputValue">
    <button @click="handleClick">Add New Note</button>
</template>

<script setup lang="ts">
import { ref } from 'vue';
import { todos } from './todo-data';

let inputValue = ref("hola");



const handleClick = () =>{
    console.warn("hey", inputValue.value);
    todos.push({
            text: inputValue.value,
            status: "Pending"
        });
        console.warn({todos});
}
</script>