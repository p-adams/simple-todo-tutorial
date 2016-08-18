<template>
    <div id="current-todos" class="container">
        <ul class="list-group">
            <li class="list-group-item" v-for="todo in todos">
                {{todo.body}}
            </li>
        </ul>
    </div>
</template>
<script>
export default{
    computed: {
        todos(){
            return this.$store.getters.todos
        }
    }
}
</script>