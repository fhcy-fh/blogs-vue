<script setup lang="ts">
import { RouterLink, RouterView } from "vue-router";
import Menu from "./components/menu.vue";
import Footer from "./components/footer.vue";
</script>

<template>
  <el-container>
    <el-header>Header</el-header>
    <el-container>
      <el-aside width="200px"><Menu></Menu></el-aside>
      <el-main><RouterView></RouterView></el-main>
    </el-container>
  </el-container>
</template>

<style scoped></style>
