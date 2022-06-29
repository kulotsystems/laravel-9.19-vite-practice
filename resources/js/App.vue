<template>
    <div>
        <h1>Laravel 9.19 Vite Practice</h1>
        <p>Modify <b><code>/resources/js/App.vue</code></b> while running <b><code>npm run dev</code></b></p>

        <button @click="count--">-</button>
        <b style="padding: 5px;">{{ count }}</b>
        <button @click="count++">+</button>

    </div>
</template>

<script>
    export default {
        name: 'App',
        components: {},
        data() {
            return {
                count: 0
            }
        },
        computed: {},
        methods: {}
    }
</script>

<style scoped>

</style>
