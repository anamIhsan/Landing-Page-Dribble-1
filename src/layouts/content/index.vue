<script setup>
    import Left from './sections/left.vue'
    import Center from './sections/center.vue'
    import Right from './sections/right.vue'
</script>

<template>
    <section class="flex justify-between items-center mt-20">
        <Left />

        <Center />

        <Right />
    </section>
</template>