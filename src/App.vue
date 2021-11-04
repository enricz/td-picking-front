<template>
  <div id="app">
    <ToolBar msg="Welcome to Your Vue.js App"/>
    <br>
    <OrderList msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import ToolBar from "@/components/ToolBar";
import OrderList from "@/components/OrderList";

export default {
  name: 'App',
  components: {
    OrderList,
    ToolBar
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
