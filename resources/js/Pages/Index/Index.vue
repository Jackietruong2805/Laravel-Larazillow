<template>
    <h1>Index</h1>
    <Link  href="/hello">Show Page</Link>
    <div class="">
        The message is {{ message }}
    </div>
</template>

<script setup>
import { Link } from '@inertiajs/vue3';

defineProps({
    message: String
});

</script>

<script>
import MainLayout from '../../Layouts/MainLayout.vue';
export default{
    layout: MainLayout
}
</script>