<template>
  <div id="app">
    <bar />
    <router-view />
    <bottom />
  </div>
</template>

<script>
import bar from '@/components/bar'
import bottom from '@/components/bottom'

export default {
  components: {bar, bottom},
  name: 'App'
}
</script>

<style>
#app {
  font-family: "Helvetica Neue", Helvetica, "PingFang SC", "Hiragino Sans GB",
    "Microsoft YaHei", "微软雅黑", Arial, sans-serif;
  text-align: center;
  margin-top: 55px;
  background-color: rgba(242, 245, 252, 0.3);
}
</style>
