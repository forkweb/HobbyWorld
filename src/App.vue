<template>
  <div id="app">
    <div class="articles_container">

      <div class="container">
        <Articles></Articles>
      </div>

    </div>

  </div>
</template>

<script>
import Articles from './components/Articles.vue'

export default {
  name: 'App',
  components: {
    Articles
  }
}
</script>

<style lang="scss" type="text/scss">
  @import "~@/style/main.scss";
</style>

