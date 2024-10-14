<script setup>
defineProps({
  niveau: {
    type: Number,
  },
});
</script>
<template>
  <h1 v-if="niveau === 1">
    <slot></slot>
  </h1>

  <h2 v-if="niveau === 2">
    <slot></slot>
  </h2>

  <h3 v-if="niveau === 3">
    <slot></slot>
  </h3>
</template>
