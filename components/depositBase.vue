<script setup lang="ts">
import DepositUserInput from "./depositUserInput.vue";
</script>

<template>
  <div className="flex flex-row ">
    <div className="flex flex-col gap-4 p-20 space-x-4 ">
      <div class="flex flex-1 flex-grow-0 pl-4">
        Please enter your user id below
      </div>
      <DepositUserInput currentUserKey="1"></DepositUserInput>
    </div>
  </div>
</template>
