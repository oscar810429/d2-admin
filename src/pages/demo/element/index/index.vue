<template>
  <d2-container :filename="filename">
    <d2-page-cover
      title="基础组件库"
      sub-title="D2Admin 集成由饿了么出品的 ElementUI">
      <img src="./image/icon.png">
    </d2-page-cover>
  </d2-container>
</template>

<script>
export default {
  data () {
    return {
      filename: __filename
    }
  }
}
</script>
