<template>
    <div>
        <h2>This is h2 of second vue</h2>
        <p>{{ msg }}</p>
    </div>
</template>
<script setup>
import { defineProps } from 'vue';
const props = defineProps({
    msg: String
})

</script>

<style scoped>
h2 {
    color: green;
}

</style>