<template>
  <div class="box text-gray-50">
    <div class="box-heading d-flex align-items-center justify-content-between">
      <div class="text-13">快速文档入口</div>
    </div>
    <ul>
      <li class="py-1">
        <docs-icon class="mr-1" /><a class="text-gray-50" href="https://mp.weixin.qq.com/debug/wxadoc/dev/index.html" target="_blank">小程序开发文档</a></li>
      <li class="py-1">
        <docs-icon class="mr-1" /><a class="text-gray-50" href="https://mp.weixin.qq.com/wiki" target="_blank">公众平台官方文档</a></li>
      <li class="py-1">
        <docs-icon class="mr-1" /><a class="text-gray-50" href="https://open.weixin.qq.com/cgi-bin/showdocument?action=dir_list&t=resource/res_list&verify=1&lang=zh_CN" target="_blank">微信开放平台文档</a></li>
      <li class="py-1">
        <docs-icon class="mr-1" /><a class="text-gray-50" href="https://work.weixin.qq.com/api/doc" target="_blank">企业微信官方文档</a></li>
      <li class="py-1">
        <docs-icon class="mr-1" /><a class="text-gray-50" href="https://www.easywechat.com/docs" target="_blank">EasyWeChat SDK 4.0 文档</a></li>
      <li class="py-1">
        <docs-icon class="mr-1" /><a class="text-gray-50" href="https://www.easywechat.com/docs/3.x" target="_blank">EasyWeChat SDK 3.x 文档</a></li>
    </ul>
  </div>
</template>

<script>
import DocsIcon from '@icons/file-document-outline'

export default {
  name: 'quick-docs',
  components: { DocsIcon }
}
</script>

<style scoped>
</style>
