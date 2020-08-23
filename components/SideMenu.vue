<template>
    <el-aside width="200px" style="background-color: rgb(238, 241, 246)">
    <el-menu 
      background-color="#77AAAD"
      text-color="#fff"
      active-text-color="#ffd04b"
    >
      <el-menu-item id="logo">
        Portfolio.me
      </el-menu-item>
      <el-menu-item>
        <nuxt-link to="/"><i class="el-icon-s-home"></i> Home</nuxt-link>
      </el-menu-item>
      <el-menu-item>
        <nuxt-link to="/works"><i class="el-icon-s-opportunity"></i> Works</nuxt-link>
      </el-menu-item>
      <el-menu-item>
        <nuxt-link to="/skills"><i class="el-icon-pie-chart"></i> Skills</nuxt-link>
      </el-menu-item>
      <el-menu-item>
        <nuxt-link to="/profile"><i class="el-icon-user"></i> Profile</nuxt-link>
      </el-menu-item>
      <el-menu-item>
        <nuxt-link to="/contact"><i class="el-icon-phone-outline"></i> Contact</nuxt-link>
      </el-menu-item>
    </el-menu>
  </el-aside>
</template>

<style>
  .el-aside {
    background-color: #D3DCE6;
    color: #333;
    text-align: center;
    line-height: 200px;
  }

  .el-menu-item a {
    display: block;
    width: 100%;
    height: 100%;
    text-decoration: none;
  }

  .el-menu-item a,
  .el-menu-item i {
    color: #ffffff;
  }

  #logo {
    font-size: 20px;
  }
</style>