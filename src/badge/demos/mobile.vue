<template>
  <div class="tdesign-mobile-demo">
    <h1 class="title">Badge 徽标</h1>
    <p class="summary">用于告知用户，该区域的状态变化或者待处理任务的数量。</p>
    <tdesign-demo-block title="01 类型" summary="徽标主要分红点、数字、文字和角标提醒">
      <div class="badge-demo">
        <div class="badge-item">
          <t-badge dot>消息</t-badge>
        </div>
        <div class="badge-item">
          <t-badge count="16">消息</t-badge>
        </div>
        <div class="badge-item">
          <t-badge count="NEW">消息</t-badge>
        </div>
        <div class="badge-item">
          <t-badge count="···">消息</t-badge>
        </div>
      </div>
      <div class="badge-demo">
        <div class="badge-item">
          <t-badge dot>
            <t-button size="small" variant="outline">小按钮</t-button>
          </t-badge>
        </div>
        <div class="badge-item">
          <t-badge count="16">
            <t-button size="small" variant="outline">小按钮</t-button>
          </t-badge>
        </div>
        <div class="badge-item">
          <t-badge count="NEW">
            <t-button size="small" variant="outline">小按钮</t-button>
          </t-badge>
        </div>
        <div class="badge-item">
          <t-badge count="···">
            <t-button size="small" variant="outline">小按钮</t-button>
          </t-badge>
        </div>
      </div>
      <t-cell-group style="overflow: hidden">
        <t-cell title="单行标题" arrow>
          <template #note>
            <t-badge dot></t-badge>
          </template>
        </t-cell>
        <t-cell title="单行标题" arrow>
          <template #note>
            <t-badge count="16"></t-badge>
          </template>
        </t-cell>
        <t-cell title="单行标题" arrow>
          <template #note>
            <t-badge count="NEW" shape="round" />
            <t-badge count="NEW" style="margin-left: 8px" />
          </template>
        </t-cell>
        <t-cell title="单行标题">
          <template #note>
            <t-badge shape="ribbon" count="NEW"> </t-badge>
          </template>
        </t-cell>
      </t-cell-group>
    </tdesign-demo-block>
  </div>
</template>
