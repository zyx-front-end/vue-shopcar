<template>
  <div>
    <my-head></my-head>
    <my-good></my-good>
    
    <my-foot></my-foot>
  </div>
</template>

<script>
//@指向的是src目录
import MyHead from '@/components/MyHead.vue'
import MyGood from '@/components/MyGood.vue'

import MyFoot from '@/components/MyFoot.vue'
  export default {
  components: { MyHead, MyGood, MyFoot },
    
  }
</script>

<style lang="less" scoped>

</style>