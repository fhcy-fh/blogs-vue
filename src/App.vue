<script setup lang="ts">
import {RouterLink,RouterView} from 'vue-router'  
import Menu from './components/menu.vue'
import Footer from './components/footer.vue';

</script>

<template>
  

  <el-container>
      <el-header><Menu></Menu></el-header>
      <el-main><RouterView></RouterView></el-main>
      <el-footer><Footer></Footer></el-footer>
    </el-container>
      
</template>

<style scoped>
</style>
