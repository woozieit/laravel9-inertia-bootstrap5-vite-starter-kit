<script setup>
    import { Head, Link } from '@inertiajs/inertia-vue3';
    import AppLayout from '@/Layouts/App.vue'

    defineProps({
        laravelVersion: String,
        phpVersion: String
    })
</script>

<template>
    <AppLayout>
        <Head title="Bienvenido" />

        <h1>Hello, Laravel 9 Inertia JS - Vue 3 Project using Bootstrap and Vite!</h1>
        <button class="btn btn-primary">Primary button</button>
    </AppLayout>
</template>

<style scoped>

</style>
