<template>
  <div class="header">
    <router-link to="/">
      <div class="iconfont header-back">&#xeb99;</div>
    </router-link>
    城市选择
  </div>
</template>

<script>
export default {
  name: 'CityHeader'
}
</script>

<style lang="stylus" scoped>
  @import "~styles/varibles.styl"
  .header
    height $headerHeight
    line-height $headerHeight
    overflow hidden
    text-align center
    color #fff
    background $bgColor
    font-size .32rem
    position relative
    .header-back
      width .64rem
      font-size .4rem
      position absolute
      top 0
      left 0
      color #fff
</style>
