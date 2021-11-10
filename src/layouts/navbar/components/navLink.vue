<script setup>
    const props = defineProps ({
        title: String
    })
</script>

<template>
    <a class="font-bold text-lg" href="#">{{ title }}</a>
</template>