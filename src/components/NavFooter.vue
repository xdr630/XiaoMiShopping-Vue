<template>
    <div class="footer">
      <div class="footer-logo">
        <img src="/imgs/logo-footer.png" alt="">
        <p>小米商城</p>
      </div>
      <div class="footer-link">
        <a href="http://www.tongyi.site" target="_blank">统一哥博客</a><span>|</span>
        <a href="http://mi.com" target="_blank">小米官网</a><span></span>
      </div>
      <div class="copyright">
        Copyright ©2020 <span class="domain">ZTY</span> All Rights Reserved.
      </div>
    </div>
</template>

<script>
export default {
  // 放入html被调用的标签名：<nav-footer></nav-footer>
  name: 'nav-footer'
}
</script>
<style lang="scss" scoped>
  @import './../assets/scss/config.scss';
  .footer{
    height:234px;
    border-top:4px solid $colorA;
    background-color:$colorB;
    color:$colorD;
    font-size:16px;
    text-align:center;
    .footer-logo{
      margin-top:46px;
      margin-bottom:31px;
      img{
        width:53px;
        height:36px;
        margin-bottom:13px;
      }
    }
    .footer-link{
      a{
        color:$colorD;
        display:inline-block;
      }
      span{
        margin:0 10px;
      }
      margin-bottom:13px;
    }
    .copyright{
      .domain{
        color:$colorA;
      }
    }
  }
</style>
