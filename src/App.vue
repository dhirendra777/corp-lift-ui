<template>
  <div id="app">
    <SignUp/>
  </div>
</template>

<script>
import SignUp from './components/SignUp'

export default {
  name: 'App',
  components: {
    SignUp
  }
}
</script>

<style>
html{
  background-color: #c2db61;
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
