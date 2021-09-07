<template>
  <div class="nav">
    <router-link to="/labels">标签</router-link>
    |
    <router-link to="/money">记账</router-link>
    |
    <router-link to="/statistics">统计</router-link>
  </div>
</template>

<script lang="ts">
export default {
  name: 'Nav'
};
</script>

<style lang="scss" scoped>//scoped可以通过自动在class后添加属性/属性选择器把class限制在当前组件内部，从而保证使用给简单的class名而不和其他组件冲突

</style>