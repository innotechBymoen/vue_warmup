<template>
    <div class="menu_card">
        <img src='http://unsplash.it/300/200?random&gravity=center' alt=''/>
        <h3>Food Title</h3>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Dolor maxime adipisci ratione, atque accusantium, velit consequuntur non aperiam repellat illo earum ut, magni maiores vero.</p>
        <h5>Item Price</h5>
    </div>
</template>

<script>
    export default {
        name: 'menu-item'
    }
</script>

<style scoped>
    .menu_card {
        max-width: 300px;
        border-radius: 15px;
        box-shadow: 3px 3px 6px gray;
    }

    .menu_card > img {
        border-top-left-radius: 15px;
        border-top-right-radius: 15px;
    }
</style>