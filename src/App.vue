<template>
  <el-config-provider namespace="ep">
    <BaseHeader />
    <div class="flex main-container">
      <BaseSide />
      <div w="full" p="4">
        <HelloWorld msg="Hello Vue 3 + Element Plus + Vite" />
      </div>
    </div>
  </el-config-provider>
</template>

<style>
#app {
  color: var(--ep-text-color-primary);
}

.main-container {
  height: calc(100vh - var(--ep-menu-item-height) - 10px);
}
</style>
