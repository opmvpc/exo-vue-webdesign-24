<script setup>
defineProps({
  type: {
    type: String,
    default: "primary",
  },
});
</script>
<template>
  <button class="btn" :class="`btn-${type}`">
    <slot></slot>
  </button>
</template>
