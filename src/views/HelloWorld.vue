<template>
  <div class="hello">
    <s-button>按钮1</s-button>
  </div>
</template>

<script>
import SButton from '../components/Button'
export default {
  name: 'HelloWorld',
  components: {
    SButton
  },
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  .hello {
    margin: 20px;
  }
</style>
