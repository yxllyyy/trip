<template>
  <div class="favor" ref="favorRef">
    <h2>favor</h2>
  </div>
</template>

<script setup>
import { ref } from 'vue'
import useScroll from '@/hooks/useScroll';

const favorRef = ref()

useScroll(favorRef)

</script>

<style lang="less" scoped>
</style>
