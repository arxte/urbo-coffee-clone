<!-- eslint-disable vue/multi-word-component-names -->
<template>
  <i :class="[icon, size, color]" class="icon"></i>
</template>

<script setup lang="ts">
const props = defineProps({
  icon: String,
  size: String,
  color: {
    type: String,
    default: 'transparent'
  }
})
</script>

<style scoped lang="scss"></style>
