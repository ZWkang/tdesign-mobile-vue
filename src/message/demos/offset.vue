<template>
  <div class="tdesign-demo-block"></div>
  <t-button variant="outline" @click="visible = true"> 偏移 </t-button>
  <t-message v-model="visible" content="偏移" :offset="[400, 100, 100]" />
</template>

<script>
import { defineComponent, ref } from 'vue';

export default defineComponent({
  setup() {
    const visible = ref(false);
    return { visible };
  },
});
</script>
