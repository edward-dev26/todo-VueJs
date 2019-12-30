<template>
    <div class="todo">
        <router-link to="/">Home</router-link>
        <ul class="todo__list">
            
        </ul>
    </div>
</template>

<script>
    export default {
        name: "ToDoList",
        props: ['todoItems']
    }
</script>

<style scoped>

</style>