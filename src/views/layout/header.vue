<template>
  <div class="header">
      <!-- head -->
      <div>首页</div>
        <!-- search -->
      <div>
        <div>search</div>
        <!-- <input type="value"  /> -->
      </div>
      
  </div>
</template>

<script>
export default {
  name: 'Header',
  data () {
    return {
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.header{
  display: flex;
  justify-content: space-between;
  align-items: center;
}
</style>
