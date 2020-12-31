<template>
  <div class="home">
    <Header /> 
    <!-- 顶部 -->
    <div>
      <Layout />
      <!-- <Menu /> -->
    </div>
  </div>
</template>

<script>
import Header from '@/views/layout/header'
import Layout from '@/views/layout/layout'
import Menu from '@/views/layout/menu'
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  },
  components:{
    Header,
    Layout,
    Menu,
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
