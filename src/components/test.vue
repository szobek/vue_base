<template>
  <div id="test">ez egy teszt -- {{t}}- <span v-if="isShowing">{{message}}</span>  <button v-on:click="isShowing=!isShowing">Klikk</button></div>
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

  },
  created() {
    console.log('indulás')
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
