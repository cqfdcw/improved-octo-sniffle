<template>

  <div id="home">
    <el-breadcrumb-item>
    <a>  线上发布</a>
    </el-breadcrumb-item>
    <el-button>默认按钮</el-button>
    <el-button type="primary">主要按钮</el-button>
    <el-button type="success">成功按钮</el-button>
    <el-button type="info">信息按钮</el-button>
    <img src="../../assets/logo.png">
    <router-view/>
      <div>
      <p>sfsgsg</p>
  </div>
  </div>

</template>

<script>
export default {
  name: 'Home'
}
</script>

<style>
#home {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
