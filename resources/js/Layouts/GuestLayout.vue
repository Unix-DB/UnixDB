<script setup>
import { ref } from 'vue';
import { Inertia } from '@inertiajs/inertia';
import { Head, Link } from '@inertiajs/inertia-vue3';
import GuestNavigation from "../Pages/GuestNavigation";

</script>

<template>
    <div>
        <head :title="title" />

        <GuestNavigation></GuestNavigation>

        <main>
            <slot />
        </main>
    </div>
</template>
