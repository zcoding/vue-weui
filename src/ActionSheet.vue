<template>
  
<div v-show="show">
  <div class="weui_mask_transition"></div>
  <div class="weui_actionsheet">
    <div class="weui_actionsheet_menu">
      <div class="weui_actionsheet_cell">示例菜单</div>
      <div class="weui_actionsheet_cell">示例菜单</div>
      <div class="weui_actionsheet_cell">示例菜单</div>
      <div class="weui_actionsheet_cell">示例菜单</div>
    </div>
    <div class="weui_actionsheet_action">
      <div class="weui_actionsheet_cell" id="actionsheet_cancel">取消</div>
    </div>
  </div>
</div>

</template>

<style lang="sass">

</style>

<script>
  
export default {
  props: {
    show: {
      type: Boolean,
      twoWay: true
    }
  }
};

</script>
