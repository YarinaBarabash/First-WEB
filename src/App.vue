<template>
  <img alt="Vue logo" src="./assets/5495723.png" class="img-logo">
  <FirstTask/>
</template>

<script>
import FirstTask from './components/FirstTask.vue'

export default {
  name: 'App',
  components: {
   FirstTask
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
.img-logo {
  width: 150px;

}
</style>
