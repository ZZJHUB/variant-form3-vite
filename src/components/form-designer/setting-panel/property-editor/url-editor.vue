<template>
  <div>
    <el-form-item label-width="0">
      <el-divider class="custom-divider">图片参数</el-divider>
    </el-form-item>
    <el-form-item label="图片地址">
      <el-input type="text" v-model="optionModel.url"></el-input>
    </el-form-item>
  </div>
</template>

<script>
  import i18n from "@/utils/i18n"

  export default {
    name: "url-editor",
    mixins: [i18n],
    props: {
      designer: Object,
      selectedWidget: Object,
      optionModel: Object,
    },
  }
</script>

<style scoped>

</style>
