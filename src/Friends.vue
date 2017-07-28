<template>
  <div>
  <h1>Firends List</h1>
  <ul>
   <li v-for="friend in friends">{{friend}}</li>
  </ul>
  </div>
</template>

<script>
export default {
  data () {
    return {
      friends:['Mamta','Sid','Gauri','mahi']
    }
  }
}
</script>

<style scoped>
h1{
color:purple;
}
</style>
