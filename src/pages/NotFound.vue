<template>
    <div class="not-found">
        <h1>404 - Page Not Found</h1>
        <p>The page you are looking for does not exist.</p>
        <router-link to="/">Go back to Home</router-link>
    </div>
</template>

<script>
export default {
    name: 'NotFound',
}
</script>

<style scoped>
h1 {
  color: red;
}
</style>