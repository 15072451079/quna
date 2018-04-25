<template>
  <div class="hello">
    <home-header></home-header>
  </div>
</template>

<script>
import HomeHeader from '../components/HomeHeader'
export default {
  name: 'Home',
  data () {
    return {
      msg: 'hello home page'
    }
 },
  components:{
      HomeHeader
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
