<script lang="ts" setup>
import A from './A.vue';

const props = defineProps<{ count: number }>()

</script>

<template>
    <A v-if="props.count > 0" :count="props.count-1" />
    <li>B</li>
</template>