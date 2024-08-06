<template>
  <el-row justify="space-between">
    <el-row align="middle">
      <el-avatar shape="square" :size="60" :src="logo" />
      <div class="header-title">河南省匠人起重机械有限公司</div>
    </el-row>
  </el-row>
</template>

<script setup lang="ts">
import logo from '../assets/logo.svg'
</script>

<style scoped>
.header-title {
  font-size: 22px;
  font-weight: 550;
  margin-left: 15px;
}
</style>
