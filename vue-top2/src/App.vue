<template>
  <div id="app">
    <router-view/>
    <van-tabbar v-model="active">
      <van-tabbar-item icon="home-o"  replace to="/" >首页</van-tabbar-item>
      <van-tabbar-item icon="search" replace to="/category">分类</van-tabbar-item>
      <van-tabbar-item icon="friends-o" replace to="/user">个人</van-tabbar-item>
    </van-tabbar>
   
  </div>
</template>

<script>
  export default{
    data(){
      return{
        active:0
      }

    }

  }
</script>
