<template>
  <div class="hello">
    <index-header />
  </div>
</template>

<script>
import header from './header.vue'
export default {
  components: {
    "index-header": header
  }
}
</script>


<style scoped>
  .hello {
    background: red;
  }
</style>
