<template>
  <div class="button-group-base">
    <t-cell-group title="块状风格">
      <t-button-group>
        <t-button theme="ghost">置底按钮</t-button>
        <t-button theme="primary">置底按钮</t-button>
      </t-button-group>
      <t-button-group>
        <t-button theme="ghost" disabled>置底按钮</t-button>
        <t-button theme="primary" disabled>置底按钮</t-button>
      </t-button-group>
    </t-cell-group>
    <t-cell-group title="菜单风格">
      <t-button-group type="menu">
        <t-button theme="ghost">置底按钮</t-button>
        <t-button theme="ghost">置底按钮</t-button>
        <t-button theme="ghost">置底按钮</t-button>
      </t-button-group>
      <t-button-group type="menu">
        <t-button theme="ghost" disabled>置底按钮</t-button>
        <t-button theme="ghost" disabled>置底按钮</t-button>
        <t-button theme="ghost" disabled>置底按钮</t-button>
      </t-button-group>
    </t-cell-group>
  </div>
</template>

<script lang="ts" setup></script>
