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
      url:'https://xxxxxxxxxxxxxxxxxx.pdf'
    }
  },
  components: {
    pdf
  }
}
</script>

<style>

</style>
