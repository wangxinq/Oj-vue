<template>
  <div id="GlobalHeader">
    <div class="menu-demo">
      <a-menu mode="horizontal" :default-selected-keys="['1']">
        <a-menu-item
          key="0"
          :style="{ padding: 0, marginRight: '38px' }"
          disabled
        >
          <div class="title-bar">
            <img class="logo" src="../assets/oj-logo.jpg" />
            <div class="title">WOJ</div>
          </div>
        </a-menu-item>
        <a-menu-item key="1">Home</a-menu-item>
        <a-menu-item key="2">Solution</a-menu-item>
        <a-menu-item key="3">Cloud Service</a-menu-item>
        <a-menu-item key="4">Cooperation</a-menu-item>
      </a-menu>
    </div>
  </div>
</template>

<script setup lang="ts"></script>
import { routes } from "@/router/routes";
<style scoped>
.title-bar {
  display: flex;
}

.logo {
  height: 48px;
}

.title {
  color: #444;
  margin-left: 16px;
  align-content: center;
}
</style>
