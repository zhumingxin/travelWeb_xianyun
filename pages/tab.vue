<template>
  <div id="app">
    <span
      v-for="(item,index) in ['news','sport','ettm']"
      :key="index"
      @click="handleClick(index)"
      :class="{active:current===index}"
    >{{item}}</span>

    <hr />
    <ul v-show="current===0">
      <li>n</li>
      <li>n</li>
      <li>n</li>
    </ul>
    <ul v-show="current===1">
      <li>s</li>
      <li>s</li>
      <li>s</li>
    </ul>
    <ul v-show="current===2">
      <li>e</li>
      <li>e</li>
      <li>e</li>
    </ul>
  </div>
</template>

<script>
export default {
  data() {
    return {
      current: 0
    };
  },
  methods: {
    handleClick(index) {
      this.current = index;
    }
  }
};
</script>

<style lang="less" scoped>
#app {
  margin: 0;
  padding: 0;
  span {
    margin: 20px;
  }
  .active {
    color: red;
  }
}
</style>