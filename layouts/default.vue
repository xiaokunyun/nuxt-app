<template>
  <div class="relative w-screen h-screen overflow-hidden">
    <!-- 头部 -->
    <Head class="fixed top-0 w-screen h-16 shadow-lg flex justify-center items-center" />
    <div class="mt-16 mb-16 w-screen h-screen">
      <!-- 内容主题 -->
      <slot />
    </div>
    <Bottom class=" w-screen h-16 bg-green-400 flex justify-center items-center" />
  </div>
</template>
<style lang="scss" scoped>
</style>