<script setup>
// TODO: 4. รู้จัก useRoute(); และ route.params;
const route = useRoute();
console.log('route.params',route.params)
</script>

<template>
    This is the portfolio id {{route.params.id}}
</template>