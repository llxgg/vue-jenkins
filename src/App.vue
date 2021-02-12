<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <div style="font-size: 30px; color:red;">测试自动化部署~~~~</div>
    <div style="font-size: 30px; color:red;">nice~~~~整套自动化终于部署成功了！</div>
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
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
