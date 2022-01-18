<template>
  <div>
    <micro-app v-if='show' name='bcs-app' url='http://localhost:3001/' baseroute='/bcs'></micro-app>
  </div>
</template>
<script>
export default {
  data () {
    return {
      show: false,
    }
  },
  mounted () {
    console.log(1)
    this.show = true
  }
}
</script>
<style lang="scss" scoped>
</style>
