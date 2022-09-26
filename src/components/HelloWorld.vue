<template>
  <div class="hello">
    <div class="grid_bg">
        <h1>标题占位</h1>
        <div class="kuang"></div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {

    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  *{
    padding: 0;
    margin: 0;
  }
  .kuang{
   background-color: #ffffff;
   width: 300px;
   height: 200px;
  }
  .grid_bg{
    background: url(https://static.zhihu.com/heifetz/assets/sign_bg.db29b0fb.png) no-repeat;
    width: 100%;
    height: 100vh;
    background-size: cover;
		background-repeat: no-repeat;
  }

</style>
