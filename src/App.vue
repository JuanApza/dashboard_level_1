<script setup>
import { RouterLink, RouterView } from 'vue-router'
import DashboardView from './views/DashboardView.vue'
import SideBar from './views/SideBar.vue';
import Headerview from './views/Headerview.vue';
</script>

<template>
  <div class="flex h-screen p-8 gap-4">
    <SideBar />
    <div class="flex flex-col flex-1">
      <Headerview />
      <main class="p-4 overflow-auto">
        <RouterView />
      </main>
    </div>
  </div>
  
</template>


