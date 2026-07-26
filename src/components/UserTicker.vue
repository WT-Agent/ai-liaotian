<template>
  <div class="glass-card ticker-card">
    <div class="ticker-wrapper">
      <div v-for="(item, index) in tickerItems" :key="index" class="ticker-item">
        <span>{{ item.text }}</span>
        <span style="color: var(--success-color); font-weight: bold;">[生成完成]</span>
      </div>
    </div>
  </div>
</template>

<script setup lang="ts">
import { ref } from 'vue';

const tickerItems = ref([
  {
    "text": "用户 136****5501 成功破解了领导微信发“在吗”的高情商回复"
  },
  {
    "text": "用户 188****2210 生成了破解女生发“随便”的晚餐推荐话术"
  },
  {
    "text": "用户 132****7790 完成了 500 人工作群冷场后的幽默接话救场"
  },
  {
    "text": "用户 151****3388 生成了面对亲戚催婚时的机智幽默反击回复"
  },
  {
    "text": "用户 176****9910 获得了刚认识的朋友发单字“嗯”的接话技巧"
  }
]);
</script>
