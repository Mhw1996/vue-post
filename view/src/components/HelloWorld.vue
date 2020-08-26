<template>
<div>
  <div class="hello">
   
  </div>
  <div class="word">
    世界黑屏
  </div>
  <div>
    小球飞入
  </div>
</div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.hello{
  width: 100px;
  height: 100px;
  background-color: red;
}
.word{
  font-size: 30px;
}
</style>
