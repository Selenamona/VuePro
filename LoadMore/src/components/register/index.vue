<template>
  <div class="regis">
    <v-header title="注册">
      <a href="#/login" slot="right">登录</a>
    </v-header>
    <v-content>
      <p><span>用户名：</span><input class="txt" type="text"></p>
      <p><span>密码：</span><input class="txt" type="password"></p>
      <p><span>邮箱：</span><input class="txt" type="email"></p>
      <p><span>手机号：</span><input class="txt" type="number"></p>
      <p><input class="check" type="checkbox">同意协议</p>
      <button>注册</button>
    </v-content>
  </div>
</template>

<script>
  export default {
      name:"Regis"
  }
</script>

<style scoped>
  p{
    width:100%;
    padding:20px 30px;
    box-sizing: border-box;
  }
  span{
    width:80px;
    display: inline-block;
  }
  .txt{
    height:20px;
    width:65%;
  }
  .check{
    margin-right:10px;
    vertical-align: middle;
  }
  button{
    width:150px;
    height:40px;
    line-height:30px;
    color:#fff;
    background: #f10;
    text-align: center;
    display: block;
    margin:20px auto;
    border: none;
    font-size: 18px;
  }

</style>

