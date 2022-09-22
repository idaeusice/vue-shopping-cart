<script setup>
    import Nav from './Nav.vue'

    defineProps({
        cartItems: {
            type: Object,
            required: true
        }
    })
</script>

<template>
    <div>
        {{ cartItems }}
    </div>
</template>

<style>

</style>