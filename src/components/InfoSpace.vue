<script setup lang="ts">
defineProps<{
  theMessage: string
}>()
</script>

<template>
  <div class="greetings">
    <div class="message">{{ theMessage }}</div>
  </div>
</template>

<style scoped>
.message {
  color: orange;
}
</style>
