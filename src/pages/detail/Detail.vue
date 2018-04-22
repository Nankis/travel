<template>
    <div class="banner">
      <img class="banner-img" src="//img1.qunarzz.com/sight/p0/201403/10/6b1f90e1ee5021b7915bee1f8b326af5.jpg_600x330_c63b6547.jpg"
           alt="">
      <div class="banner-info">
        <div class="banner-tittle">
          大连圣亚海洋世界(AAAA景区)
        </div>
        <div class="banner-number"><span class="iconfont">&#xe632;</span>
          39
        </div>
      </div>
    </div>
</template>

<script>
import DetailBanner from './components/Banner'
export default {
  name: 'Detail',
  components: {
    DetailBanner
  }
}
</script>

<style lang="stylus" scoped>
  .banner
    position: relative
    overflow: hidden
    height: 0
    padding-bottom: 55%
    .banner-img
      width: 100%
    .banner-info
      display: flex
      position: absolute
      left: 0
      right: 0
      bottom: 0
      line-height: .6rem
      color: #fff
      background-image: linear-gradient(top, rgba(0, 0, 0, 0), rgba(0, 0, 0, 0.8))
      .banner-tittle
        flex: 1
        font-size: .32rem
        padding: 0 .2rem
      .banner-number
        height: .32rem
        line-height: .32rem
        margin-top: .14rem
        padding: 0 .4rem
        border-radius: .2rem
        background: rgba(0, 0, 0, .8)
        font-size: .24rem
        .banner-icon
          font-size: .24rem
</style>
