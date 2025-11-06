<script setup lang="ts">
const props = defineProps<{
  modelValue: boolean
}>()
</script>

<template>
  <div>
    <h1>Hello World</h1>
    <slot />
  </div>
</template>