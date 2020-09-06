<template>
  <div id="app">
    <div id="nav">
      <router-link to="/app1">
        app1
      </router-link>
      <span style="margin: 0 20px"> | </span>
      <router-link to="/app2">
        app2
      </router-link>
    </div>
    <div id="microApp">
      <router-view />
    </div>
  </div>
</template>

<script>
export default {
  name: 'App',
}
</script>

<style>
  #app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
  }

  #nav {
    padding: 30px;
    display: flex;
    justify-content: center;
    margin-bottom: 20px;
  }

  /*#nav a {*/
  /*  font-weight: bold;*/
  /*  color: #2c3e50;*/
  /*}*/

  /*#nav a.router-link-exact-active {*/
  /*  color: #42b983;*/
  /*}*/
</style>
