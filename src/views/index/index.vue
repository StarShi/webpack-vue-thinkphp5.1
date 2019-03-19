<template>
  <div id="app" class='containera'>
      <div style="width:100px;height:100px;background-color:black;">
          <img src="/static/images/article_bg.png" width="100%" height="100%">
      </div>
  </div>
</template>

<script>

export default {
  name: 'App',
  components:{
  }
}
</script>

<style>

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
.container{
  width:100%;
  min-height:100%;
  overflow-y: auto;
}
body{
  background-color: blue;

}
</style>