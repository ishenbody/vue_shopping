<template>
  <div id="app">
    <img src="./assets/logo.png">
    <div>
      <HelloWorld/>
    <el-button>el-button</el-button>
    </div>
  </div>
</template>
<script>
import HelloWorld from './components/HelloWorld.vue'
export default {
  name: 'app',
  components: {
    HelloWorld
  }
}
</script>
