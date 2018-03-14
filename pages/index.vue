<template>
  <div class="container">
    <Header></Header>
  </div>
</template>

<script>
import Header from '~/components/header.vue'

export default {
  components: {
    Header
  }
}
</script>

<style lang="scss">
.container {
  min-height: 100vh;
  color: $someVariable;
}
</style>
