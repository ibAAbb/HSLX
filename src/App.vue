<template>
  <div id="app">
    <!-- <Topbar></Topbar> -->
    <!-- <NavMenu class="ib"></NavMenu>
    <router-view class="ib"></router-view> -->
    <router-view></router-view>
  </div>
</template>

<script>
import NavMenu from "@/components/Sidebar.vue";
import Topbar from "@/components/Topbar.vue";
import Breadcrumb from "@/components/Breadcrumb.vue";
import index from "@/components/index.vue";
export default {
  components: {
    NavMenu,
    // Topbar,
    index,
  },
};
</script>

<style lang="less" scope>
// .ib {
//   margin-left: px;
// }
</style>
