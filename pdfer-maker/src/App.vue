<template>
  <div id="app">
    <pdf ></pdf>
  </div>
</template>

<script>
import pdf from './lib/index.vue'

export default {

  name: 'app',
  data(){
    return{
      url:'https://ycism-crm-bj001.oss-cn-beijing.aliyuncs.com/crm/confirm/2019-10-22/Pdf201910221620529501.pdf'
    }
  },
  components: {
    pdf
  }
}
</script>

<style>

</style>
