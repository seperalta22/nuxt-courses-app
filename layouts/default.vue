<script setup lang="ts">
import Navbar from '~~/components/layout/navbar.vue';
</script>

<template>
    <div class="h-screen">
        <Navbar />
        <!--!  This is where the page content will be rendered -->
        <slot />
    </div>
</template>