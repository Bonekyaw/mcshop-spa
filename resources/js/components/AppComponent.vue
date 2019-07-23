<template>
    <div>

        <p>
            <router-link :to="{ name: 'home' }">Home</router-link> |
            <router-link :to="{ name: 'category' }">Category</router-link> |
            <router-link :to="{ name: 'brand' }">Brand</router-link>
        </p>
        <h1>Vue Router Demo App</h1>

        <div class="container">
            <router-view></router-view>
        </div>
    </div>
</template>
<script>
    export default {}
</script>