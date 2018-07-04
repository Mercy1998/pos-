<template>
<div class="left-nav">
  <ul>
    <li>
      <i class="icon iconfont icon-qian"></i>
      <div>收银</div>
    </li>
    <li>
      <i class="icon iconfont icon-duogouwu"></i>
      <div>店铺</div>
    </li>
    <li>
      <i class="icon iconfont icon-canyin"></i>
      <div>商品</div>
    </li>
    <li>
      <i class="icon iconfont icon-geren2"></i>
      <div>会员</div>
    </li>
    <li>
      <i class="icon iconfont icon-zhinengyouhua"></i>
      <div>统计</div>
    </li>
  </ul>
</div>
</template>

<script>
  export default {
name:'leftNav'
  }
</script>

<style>
.left-nav{
  color: #fff;
  font-size: 10px;
  height:100% ;
  background-color: #1d8ce0;
  float: left;
  width: 6%;

}
  .iconfont{
    font-size: 30px;

  }
  .left-nav ul{
    padding: 0px;
    margin: 0px;
  }
  .left-nav li{
    list-style: none;
    text-align: center;
    border-bottom:1px solid #825852 ;
    padding: 8px;
  }
</style>
