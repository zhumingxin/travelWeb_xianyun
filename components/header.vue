<template>
  <div>
    <div class="container">
      <el-row type="flex" class="header">
        <a href="/" class="logo">
          <img src="../assets/imgs/logo.jpg" alt />
        </a>
        <el-col>
          <el-row type="flex" class="nav_bar">
            <nuxt-link to="/">首页</nuxt-link>
            <nuxt-link to="/air">飞机</nuxt-link>
            <nuxt-link to="/hotel">酒店</nuxt-link>
            <nuxt-link to="/post">旅游攻略</nuxt-link>
          </el-row>
        </el-col>
        <nuxt-link to="/user/login" class="login">登录/注册</nuxt-link>
      </el-row>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="less" scoped>
.header {
  box-shadow: 0 2px 2px #eee;
  width: 1000px;
  margin: 0 auto;
  .logo {
    height: 60px;
    img {
      width: 156px;
      padding-top: 9px;
    }
    .login {
      width: 60px;
    }
  }
  .nav_bar {
    flex: 1;
    a {
      height: 60px;
      line-height: 60px;
      display: block;
      padding: 0 20px;

      &:hover {
        color: #409eff;
        border-bottom: 5px solid #409eff;
        box-sizing: border-box;
      }
    }
    .nuxt-link-exact-active {
      background-color: #409eff;
      color: #fff;
    }
  }
}
</style>