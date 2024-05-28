<script setup lang="ts">

</script>

<template>
    <div>
        <h1>X</h1>
        <ul>
            <li>
                <NuxtLink href="/login">Login</NuxtLink>
            </li>
            <li>
                <NuxtLink href="/register">Register</NuxtLink>
            </li>
        </ul>

        <slot/>
    </div>
</template>

<style scoped>

</style>