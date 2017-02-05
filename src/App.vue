<template>
  <div id="app">
    <h1>go</h1>
    <router-view></router-view>
    <hr>
    <router-link to="/">Home</router-link>
    <router-link to="/users/10">Users10</router-link>
    <router-link to="/users/12">Users12</router-link>
    <hr>
  </div>
</template>

<script>
  export default {
    data () {
      return {}
    }
  }
</script>

<style>

</style>
