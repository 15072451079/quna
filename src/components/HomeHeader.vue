<template>
  <div class="header">
    <div class="header-left">
      <div class="iconfont back-icon">&#xe624;</div>
    </div>
    <div class="header-input">
      <span class="iconfont">&#xe632;</span>
      输入城市/景点/游玩/主题</div>
    <div class="header-right">
      城市
      <span class="iconfont city-icon">&#xe64a;</span>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HomeHeader',
  data () {
    return {
      msg: 'home header'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<!-- 1rem=50px==html的值 -->
<style lang='stylus' scoped>
    @import '../assets/styles/varibles.styl';
    .header
        display:flex
        height : 0.86rem
        line-height :0.86rem
        background: $bgColor
        color:#fff
        .header-left
            width: 0.64rem
            float: left
            .back-icon
                text-align :center
                font-size :.4rem
        .header-input
          flex:1
          background :#fff
          border-radius :0.1rem
          height :.64rem
          line-height :.64rem
          margin-top :.12rem
          margin-left :.2rem
          padding-left :.2rem
          margin-right:.2rem
          color :#ccc
        .header-right
            width :1.24rem
            float: right 
            .city-icon
                font-size :.24rem
                


</style>
