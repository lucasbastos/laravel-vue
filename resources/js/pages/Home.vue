<template>
    <div>
        <h1 class="text-3xl font-bold underline">
    Hello world!
  </h1>
    </div>
</template>

<script setup>
import { defineProps } from 'vue';

const props = defineProps({
    name: {
        type: String,
        required: true
    }
});

</script>

<style lang="scss" scoped>

</style>