<template>
  <div id="nav">
      <router-link to="/home"><i class="iconfont">&#xe6bb;</i>首页</router-link>
      <router-link to="/study"><i class="iconfont">&#xe742;</i>学习</router-link>
      <router-link to="/publish"><i class="iconfont" style="font-size:30px;">&#xe6d9;</i></router-link>
      <router-link to="/message"><i class="iconfont">&#xe73d;</i>消息</router-link>
      <router-link to="/my"><i class="iconfont">&#xe735;</i>我的</router-link>
    </div>
</template>

<script>
export default {
  name: '',
  data() { 
    return {

    }
  }
 }
</script>

<style lang="scss" scoped>
  #nav{
    display: flex;
    justify-content: space-between;
    align-items: center;
    position: fixed;
    bottom: 0;
    left: 0;
    width: 100%;
    height: 50px;
    padding: 0 6%;
    z-index: 1000;
    border-top: 2px solid #F5F5F5;
    background-color: #fff;
    a{
       display: flex;
      justify-content: space-between;
      align-items: center;
      flex-flow: column wrap;
      &.a-active{
        color: #E4C04D;
      }
      i{
        font-size: 24px;
      }
    }
  }
</style>