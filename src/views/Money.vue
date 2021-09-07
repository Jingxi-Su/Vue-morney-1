<template>
  <div class="nav-wrapper">
    <div class="content">
      Money.vue
    </div>
    <Nav/>
  </div>

</template>

<script lang="ts">
export default {
  name: 'Money'
};
</script>

<style lang="scss" scoped>
.nav-wrapper {
  display: flex;
  flex-direction: column;
  height: 100vh;
}

.content {
  overflow: auto;//超出后自动滚动
  flex-grow: 1; //尽量把所有高度都给content
}
</style>