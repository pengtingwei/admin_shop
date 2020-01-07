<template>
  <el-breadcrumb separator-class="el-icon-arrow-right">
    <el-breadcrumb-item :to="{ path: '/home' }">首页</el-breadcrumb-item>
    <el-breadcrumb-item>{{ data1 }}</el-breadcrumb-item>
    <el-breadcrumb-item>{{ data2 }}</el-breadcrumb-item>
  </el-breadcrumb>
</template>

<script>
export default {
  props: ['data1', 'data2']
}
</script>

<style lang="less" scoped></style>
