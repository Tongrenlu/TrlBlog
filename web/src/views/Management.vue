<template>
  <div class="Management">
    <div class="title">
      <h1>Trl`s Blog Management System</h1>
    </div>
    <el-row type="flex" justify="center">
      <el-col :span="6">

        <el-tabs stretch>
          <el-tab-pane label="普通登录">
            <el-row>
              <el-col :span="2">
                <span class="fa fa-user fa-lg loginIcon"></span>
              </el-col>
              <el-col :span="22">
                <el-input class="loginInput" placeholder="请输入用户名" clearable></el-input>
              </el-col>
              <el-col :span="2">
                <span class="fa fa-key fa-lg loginIcon"></span>
              </el-col>
              <el-col :span="22">
                <el-input class="loginInput" placeholder="请输入密码" type="password" clearable></el-input>
              </el-col>
              <el-col :span="24">
                <label class="passwordHint">密码提示</label>
              </el-col>
              <el-col :span="24">
                <el-button class="loginBotton" type="primary">登录</el-button>
              </el-col>
            </el-row>
          </el-tab-pane>
          <el-tab-pane label="手机登录">
            <el-input class="loginInput" placeholder="暂未开放" disabled></el-input>
          </el-tab-pane>
        </el-tabs>

      </el-col>
    </el-row>

  </div>
</template>

<style scoped>
.title {
  margin-top: 150px;
}
.title h1 {
  font-size: 35pt;
}
.loginInput {
  margin-top: 10px;
}
.loginIcon {
  margin-top: 22px;
}
.passwordHint {
  float: right;
  margin-top: 10px;
  font-size: 10pt;
  color: #c0c4cc;
}
.loginBotton {
  width: 100%;
  margin-top: 10px;
}
</style>
