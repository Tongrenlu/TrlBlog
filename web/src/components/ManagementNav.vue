<template>
  <el-row>
    <el-col :span="2">
      <el-menu default-active="1">
        <h3>Trl`s Blog</h3>
        <el-menu-item index="1">
          <i class="el-icon-menu"></i>
          <span slot="title">导航二</span>
        </el-menu-item>
        <el-menu-item index="2">
          <i class="el-icon-menu"></i>
          <span slot="title">导航二</span>
        </el-menu-item>
        <el-menu-item index="3">
          <i class="el-icon-document"></i>
          <span slot="title">导航三</span>
        </el-menu-item>
        <el-menu-item index="4">
          <i class="el-icon-setting"></i>
          <span slot="title">导航四</span>
        </el-menu-item>
      </el-menu>
    </el-col>

  </el-row>

</template>

<script>
export default {
  name: "ManagementNav"
};
</script>


<style>

</style>
