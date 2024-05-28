<script setup lang="ts">
    definePageMeta({
        middleware: ['auth']
    })
</script>

<template>
    <div>
        <h1>Home</h1>
        <p>Precisa estar autenticado!</p>
    </div>
</template>


<style scoped>

</style>