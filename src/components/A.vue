<script lang="ts" setup>
import B from "./B.vue";

const props = defineProps<{ count: number }>()

</script>

<template>
    <B :count="props.count-1" />
    <li>A</li>
</template>