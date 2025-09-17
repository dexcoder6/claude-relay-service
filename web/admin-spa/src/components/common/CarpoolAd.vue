<template>
  <div class="carpool-ad">
    <!-- 桌面版：横向布局 -->
    <div
      class="hidden items-center justify-between rounded-lg border border-blue-300 bg-gradient-to-r from-blue-500 to-purple-600 p-4 text-white shadow-lg dark:border-purple-400 dark:from-blue-600 dark:to-purple-700 sm:flex"
    >
      <div class="flex items-center space-x-4">
        <div class="flex-shrink-0">
          <span class="text-2xl">🚗</span>
        </div>
        <div>
          <h3 class="mb-1 text-lg font-bold">拼车服务</h3>
          <p class="text-sm opacity-90">我们还提供专业的拼车服务：</p>
          <div class="mt-2 text-xs opacity-80">
            <div class="flex flex-wrap gap-4">
              <span>• Claude Code Max 20X: 节省60%+</span>
              <span>• CodeX: 多模型支持，更多选择</span>
              <span>• 稳定可靠: 专业运维和技术保障</span>
              <span>• 安全可控: 使用本项目搭建，数据安全</span>
            </div>
          </div>
        </div>
      </div>
      <div class="ml-2 flex-shrink-0">
        <a
          class="inline-flex items-center rounded-md bg-white px-4 py-2 font-medium text-blue-600 shadow-sm transition-colors hover:bg-blue-50 dark:bg-gray-100 dark:text-blue-700 dark:hover:bg-gray-200"
          href="https://pincc.ai/join-carpool"
          target="_blank"
        >
          <i class="fas fa-rocket mr-1"></i>
          立即加入
        </a>
      </div>
    </div>

    <!-- 移动版：纵向布局 -->
    <div
      class="rounded-lg border border-blue-300 bg-gradient-to-br from-blue-500 to-purple-600 p-4 text-white shadow-lg dark:border-purple-400 dark:from-blue-600 dark:to-purple-700 sm:hidden"
    >
      <div class="mb-2 text-center">
        <div class="mb-2 text-3xl">🚗</div>
        <h3 class="mb-1 text-lg font-bold">拼车服务</h3>
        <p class="text-sm opacity-90">我们还提供专业的拼车服务</p>
        <div class="mt-2 text-xs opacity-80">
          <div class="space-y-1">
            <div>• Claude Code Max 20X: 节省60%+</div>
            <div>• CodeX: 多模型支持，更多选择</div>
            <div>• 稳定可靠: 专业运维和技术保障</div>
            <div>• 安全可控: 使用本项目搭建，数据安全</div>
          </div>
        </div>
      </div>
      <div class="text-center">
        <a
          class="inline-flex w-full items-center justify-center rounded-md bg-white px-4 py-2 font-medium text-blue-600 shadow-sm transition-colors hover:bg-blue-50 dark:bg-gray-100 dark:text-blue-700 dark:hover:bg-gray-200"
          href="https://pincc.ai/join-carpool"
          target="_blank"
        >
          <i class="fas fa-rocket mr-1"></i>
          立即加入
        </a>
      </div>
    </div>
  </div>
</template>

<script setup>
// 官方拼车服务广告组件
// 推广专业的API中转服务，响应式设计，支持明亮/暗黑模式
</script>

<style scoped>
.carpool-ad {
  /* 确保广告有足够的视觉吸引力 */
  position: relative;
}

/* 添加轻微的动画效果 */
.carpool-ad:hover {
  transform: translateY(-1px);
  transition: transform 0.2s ease-in-out;
}

/* Tailwind CSS 的 dark: 类会自动处理暗黑模式的渐变背景 */
</style>
