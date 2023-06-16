<template>
    <div>Test</div>
</template>

<script setup lang="ts">
interface Extended extends Test {
    email: string;
}

defineProps<Extended>();
</script>

<style scoped></style>
