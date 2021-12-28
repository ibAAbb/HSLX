<template>
  <el-container style="height: 100%">
    <el-aside width="auto"><Sidebar></Sidebar></el-aside>
    <el-container>
      <el-header>Header</el-header>
      <el-main>Main</el-main>
    </el-container>
  </el-container>
</template>

<script>
import Sidebar from "@/components/Sidebar.vue";
export default {
  data() {
    return {};
  },
  components: {
    Sidebar,
  },
};
</script>

<style lang="less" >
* {
  padding: 0;
  margin: 0;
}
html,
body,
#app,
.el-container {
  height: 100%;
}

// body > .el-container {
//   margin-bottom: 40px;
// }

// .el-container:nth-child(5) .el-aside,
// .el-container:nth-child(6) .el-aside {
//   line-height: 260px;
// }

// .el-container:nth-child(7) .el-aside {
//   line-height: 320px;
// }
</style>