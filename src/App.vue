<script setup>

  // setup 是一个开关 容许在script书写组合式API
  //导入
  //import { reactive, ref, computed } from 'vue'

  // 传入一个对象类型的参数 变量接收。reactive里的对象数据就变成响应式的数据了
  //const state = reactive({对象类型数据})


</script>

<template>
  <!-- 准备一个一级路由出口组件 -->
  <router-view></router-view>
  <div class="test">
    test scss
  </div>
</template>

<style scoped lang="scss">
.test {
  color: $warnColor;
}
/* scoped 使用得定义的样式只在本页面内生效  */

</style>