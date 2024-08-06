<template>
  <el-container>
    <el-header class="layout-header">
      <ContainerHead />
    </el-header>
    <el-main>Main</el-main>
    <el-footer>Footer</el-footer>
  </el-container>
</template>

<script setup lang="ts">
import ContainerHead from './components/ContainerHead.vue'
</script>

<style scoped>
.layout-header {
  padding: 20px 60px;
  height: auto;
}
</style>
