<template>
    <button v-bind="$attrs">
        <slot />
    </button>
</template>
<script>
export { default as VButton } from './VButton.vue';
</script>