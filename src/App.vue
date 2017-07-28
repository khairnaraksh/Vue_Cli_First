<template>
  <div>
  <h1>{{title}}</h1>
  <friends></friends>
  </div>
  </template>

<script>
 import Friends from './Friends.vue'

export default {
components:{
friends:Friends
},
  data () {
    return {
      title: 'Hello Friends...'
    }
  }
}
</script>

<style scoped>
  h1{
      color:red;
    },
  friends{
    color:yellow;
    }
</style>
