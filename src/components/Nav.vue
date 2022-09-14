<script setup>
    import NavLink from '../components/NavLink.vue'
    defineProps({
        msg: {
            type: String,
            required: true
        }
    })
</script>

<template>
    <div class="links">
        <NavLink />
    </div>
</template>