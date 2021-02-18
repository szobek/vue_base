<template>
  <div id="test">ez egy teszt -- {{t}}- <span v-if="isShowing">{{message}}</span>  <span v-on:click="isShowing=!isShowing">Klikk</span></div>
</template>

<script>
export default {
  name: 'test',
  data() {
    return {
      isShowing: false,
      message: 'teszt'
    }
  },
  props: {
    t: String,
    z: Object
  },
  methods: {
    fn(){
console.log("működik")
      //console.log(this.z)
    }
  },

};
</script>

<style scoped>

</style>
