<template>
  <svg class="s-icon">
    <use :xlink:href="`#i-${name}`"></use>
  </svg>
</template>
<script>
import '../assets/svg/svg'

export default {
  name: 'Icon',
  props: {
    name: {
      type: String
    }
  }
}
</script>
<style lang="scss" scoped>
.s-icon {
  width: 1em;
  height: 1em;
}
</style>
