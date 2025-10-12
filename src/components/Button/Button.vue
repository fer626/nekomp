<script setup lang="ts">
</script>

<template>
  <button class="btn">
    <slot />
  </button>
</template>

<style scoped>
  .button {
    padding: 0.5em 1em;
    border: none;
    border-radius: 4px;
    background-color: #42b983;
    color: white;
    cursor: pointer;
    font-size: 1em;
    transition: background-color 0.3s ease;
  }
</style>