<template>
  <div id="app">

    <span><HelloWorld msg="Welcome"/></span>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'


export default {
  name: 'app',
  components: {
    HelloWorld
  }
}
</script>

<style lang="sass">
div
  display: flex
</style>
