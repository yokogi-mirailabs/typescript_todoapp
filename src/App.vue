<script setup lang="ts">
import AppNavi, { MenuItem } from "./components/AppNavi.vue";

const menuItems: MenuItem[] = [
  {
    title: "Home",
    url: "/",
  },
  {
    title: "ToDo",
    url: "/todo",
  },
];
</script>

<template>
  <AppNavi class="text-lg" title="Todo App" :menu-items="menuItems"></AppNavi>
</template>