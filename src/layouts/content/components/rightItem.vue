<script setup>
    const props = defineProps ({
        title: String,
        desc: String
    })
</script>

<template>
    <div class="flex items-center space-x-4">
        <div class="bg-[#f07911] text-white rounded-2xl p-3 h-[70px] w-16 col-span-1 flex items-center">
            <slot />
        </div>
        <div class="col-span-1">
            <h1 class="text-xl font-semibold">{{ title }}</h1>
            <p class="text-[#75756d]">{{ desc }}</p>
        </div>
    </div>
</template>