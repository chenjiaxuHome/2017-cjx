<template>
  <div class="hello">
    <input type="text" v-model="msg">
    {{ msg }}
  </div>
</template>

<script>
export default {
  name: 'header',
  data () {
    return {
      msg: 'header'
    }
  }    
}
</script>


<style scoped>
  .hello {
    background: pink;
  }
</style>
