<template>
  <div id="app">
    <vHeader></vHeader>
    <vContent></vContent>
  </div>
</template>

<script>
import vHeader from './components/vHeader'
import vContent from './components/vContent'
export default {
  name: 'app',
  components: {
    vHeader,
    vContent
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
