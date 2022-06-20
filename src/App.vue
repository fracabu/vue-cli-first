<template>
  <div>
    <Title></Title>


  </div>
</template>

<script>
import Title from './components/Title.vue';


export default {
  components: {
    Title,


  },
  data() {
    return {
      message: 'Hello Vue',
    }
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
