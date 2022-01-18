<template>
 <div>
    <span>公共标题</span>
    <nuxt></nuxt>
 </div>

</template>
<script>
import microApp from '@micro-zoe/micro-app'
export default {
  mounted () {
    microApp.start()
  }
}
</script>

<style>

</style>
