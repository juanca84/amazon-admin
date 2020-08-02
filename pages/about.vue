<template>
    <div>
        <h1>About Me</h1>
        <p>{{name}}</p>
        <input v-model="name" type="text">
        <button @click="onClick">Click me</button>
    </div>
</template>

<script>
    export default {
        data () {
            return {
                name: 'About me I am awesome'
            }
        },
        methods:{
            onClick() {
                alert(this.name)
            }
        }
    }
</script>

<style lang="scss" scoped>

</style>