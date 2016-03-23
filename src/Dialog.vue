<template>
  
<div class="weui_dialog_alert" v-show="show">
  <div class="weui_mask"></div>
  <div class="weui_dialog">
    <div class="weui_dialog_hd">
      <strong class="weui_dialog_title">弹窗标题</strong>
    </div>
    <div class="weui_dialog_bd">弹窗内容，告知当前页面信息等</div>
    <div class="weui_dialog_ft">
      <a href="javascript:;" class="weui_btn_dialog primary">确定</a>
    </div>
  </div>
</div>

</template>

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
