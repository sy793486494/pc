<template>
  <div class="header">
    城市选择
    <router-link to="/">
      <div class="iconfont header-back">&#xe8b5;</div>
    </router-link>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="stylus" scoped>
  .header
    position: relative
    overflow: hidden
    height: 0.86rem
    line-height: 0.86rem
    text-align: center
    color: #fff
    background: #00bcd4
    font-size: 0.3rem
    .header-back
      position: absolute
      top: 0
      left:0
      width: 0.64rem
      text-align: center
      font-size: 0.4rem
      color: #fff
</style>