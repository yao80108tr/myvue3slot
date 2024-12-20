<template>
  <div id="app">
    <!-- 插入 SlotMachine 組件 -->
    <SlotMachine />
  </div>
</template>

<script setup>
// 引入 SlotMachine 組件
import SlotMachine from './components/SlotMachine.vue';
</script>

<style>
/* 主組件的樣式 */
#app {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  background-color: #222; /* 添加深色背景 */
}
</style>
