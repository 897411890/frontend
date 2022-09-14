<template>
  <div class="hello">
    <div class="grid_bg"></div>
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
    width: 100%;
    height: 100vh;
  }
  .grid_bg{
    background: url(https://static.zhihu.com/heifetz/assets/sign_bg.db29b0fb.png) no-repeat;
    width: 100%;
    height: 100vh;
    background-size: cover;
		background-repeat: no-repeat;
  }

</style>
