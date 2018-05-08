<template>
  <div id="app">
    <img src="./assets/logo.png">
    <div class="">
      <ul>
        <li><router-link to="/">Home</router-link></li>
        <li><router-link to="/FirstRoute/Javed">First Route</router-link></li>
        <li><router-link to="/FirstRoute/Javed/child">First Route Child</router-link></li>
      </ul>
    </div>
    <router-view/>
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
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
