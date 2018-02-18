<template>
  <div class="faq">
    <h1>{{ msg }}</h1>
    <h2>faq</h2>
  </div>
</template>

<script>
export default {
  name: 'faq',
  data () {
    return {
      msg: 'Welcome to Your Vue.js faq'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="sass" scoped>
@import '../mq'

</style>
