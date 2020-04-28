<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <div class="test">
      张浩浩测试!!!
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld
  }
}
</script>
<style lang="less" scoped>
  .test{
    width: 2.4rem;
    height: 2.4rem;
    text-align: center;
    line-height: 2.4rem;
    border: 1px solid #ccc;
  }
</style>
