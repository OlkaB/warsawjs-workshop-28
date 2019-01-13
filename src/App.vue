<template>
  <div id="app">
    <router-view/>

    <div class="row">
      <md-content class="md-elevation-1">1</md-content>
      <md-content class="md-elevation-4">4</md-content>
      <md-content class="md-elevation-8">8</md-content>
    </div>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  margin-top: 60px;
}

.row {
  display: flex;
}
</style>
