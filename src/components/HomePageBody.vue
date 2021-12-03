<template>
    <div>
        <h1>Welcome to the page!</h1>
        <menu-item></menu-item>
    </div>
</template>

<script>
import MenuItem from './MenuItem.vue';

    export default {
        name: 'home-page-body',
        components: {
            MenuItem,
        },
    }
</script>

<style scoped>

</style>