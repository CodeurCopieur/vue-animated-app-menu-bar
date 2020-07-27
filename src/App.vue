<template>
  <div id="app">
    <AppBar></AppBar>
  </div>
</template>

<script>
import AppBar from './components/AppBar.vue'

export default {
  name: 'App',
  components: {
    AppBar
  }
}
</script>

<style>

@import url('./assets/scss/index.scss');
@import url('https://use.fontawesome.com/releases/v5.8.2/css/all.css');
@import url('https://fonts.googleapis.com/css?family=Nunito&display=swap');

#app {
  font-family: 'Nunito', Arial, Helvetica, sans-serif;
  font-size: 1rem;
  color: #333;
  width: 100%;
  min-height: 100vh;
  overflow: hidden;
}
</style>
