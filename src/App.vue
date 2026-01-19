<script setup>
import { RouterLink, RouterView } from 'vue-router'
import DashboardView from './views/DashboardView.vue'
import SideBar from './views/SideBar.vue';
import Header from './views/Header.vue';
</script>

<template>
  <div class="flex h-screen p-4">
    <SideBar />
    <div class="flex flex-col flex-1">
      <Header />
      <main class="p-4 overflow-auto">
        <RouterView />
      </main>
    </div>
  </div>
  
</template>


