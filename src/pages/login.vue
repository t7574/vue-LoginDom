<template>
  <div class="login">   
<div style="margin: 20px;"></div>
<el-form  label-width="80px" ref="form" :model="form">
  <el-form-item label=用户名:>
    <el-input v-model="from.username"></el-input>
  </el-form-item>
  <el-form-item label="密码:">
    <el-input v-model="from.password"></el-input>
  </el-form-item>
  <el-form-item class="login-btn">
   <el-button type="primary" class="login-btn" @click="getLogin">登录</el-button>
  </el-form-item>
</el-form>
  </div>
</template>

<script>
  export default {
    data() {
      return {
       
      };
    },
    created() {
      
    },
    methods: {
      
    },
  }
</script>
<style lang="less" scoped>
.login{
  width:30%;
  font-size: 20px;
  margin: 15% auto;
  padding: 50px;  
  box-shadow: 3px 3px 5px #ccc;
  .login-btn{
   width:80%;
   margin-left: 10%;
  }
}
</style>
