<template>
  <div>
    <HelloWorld/>
  </div>
</template>

<script>
import HelloWorld from './views/HelloWorld.vue'

export default {
  name: 'app',
  components: {
    HelloWorld
  }
}
</script>

<style lang="scss">
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
</style>
