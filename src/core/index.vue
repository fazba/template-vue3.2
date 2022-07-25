<template>
  <div class="module">{{ msg }}</div>
</template>
<script setup lang="ts">
defineProps<{
  msg: string;
}>();
</script>
<style lang="less" scoped>
.module {
  height: 100%;
  font-size: 20px;
  text-align: center;
}
</style>
