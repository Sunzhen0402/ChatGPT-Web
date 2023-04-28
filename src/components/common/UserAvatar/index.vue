<script setup lang='ts'>
import { computed } from 'vue'
import { useUserStore } from '@/store'

const userStore = useUserStore()

const userInfo = computed(() => userStore.userInfo)
</script>

<template>
  <div class="flex flex-col items-center overflow-hidden">
    <div class="w-100 h-30 overflow-hidden shrink-0">
      <img
        src="http://101.43.221.136/upload/PineCones.jpg"
        alt="Random Image"
        width="100"
        height="40"
      >
    </div>
  </div>
</template>
