<template>
  <div id="app">
        <div  id="vditor"  class="vditor"/>
  </div>
</template>
<script>
import Vditor from 'vditor'
import 'vditor/dist/index.css'

export default {
  data () {
    return {
      vditor : null
    }
  },
  mounted() {
    this.vditor = new Vditor('vditor');
  }
}
</script>
<style>

</style>
