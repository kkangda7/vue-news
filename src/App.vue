<template>
  <div id="app">
    <tool-bar></tool-bar>
    <!-- control + option > click 링크이동 -->
    <router-view></router-view>
  </div>
</template>

<script>
import ToolBar from './components/ToolBar.vue'

export default {
  components: { ToolBar },
}
</script>

<style>
body {
  margin: 0;
  padding: 0;
}
</style>
