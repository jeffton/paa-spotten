<template>
  <h2>{{model}}</h2>
</template>


<script>
  export default {
    data () {
      return { 
        model: {}
      }
    },
    created () {
      this.model = 'data goes here'
    }
  }
</script>