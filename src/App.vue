<template>
  <van-grid :column-num="2">
    <van-grid-item v-for="value in 4" :key="value" icon="photo-o" text="文字" />
  </van-grid>
</template>

<script>
// 原始代码
import { Button,Grid, GridItem } from 'vant';
export default {
  name: 'App',
  components: {
    [Button.name]:Button,
    [Grid.name]:Grid,
    [GridItem.name]:GridItem
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
