<script setup lang="ts">
const props = defineProps<{
  currentUserKey?: string;
}>();
</script>

<template>
  <div class="flex flex-col">
    <input
      name="name"
      id="name"
      type="text"
      class="w-20 border-2 border-solid"
    />
  </div>
</template>
