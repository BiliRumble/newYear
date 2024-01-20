<template>
  <main>
    <H1>春节倒计时</H1>
    <timeBox />
  </main>
</template>

<script setup lang="ts">
import timeBox from './components/timeBox.vue';
</script>

<style scoped lang="scss">
main {
  display: flex;
  width: 100vh;
  height: 100vw;
}
</style>
