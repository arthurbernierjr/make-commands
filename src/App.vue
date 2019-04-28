<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld
      v-for="(file, index) in listOffiles"
      :msg="file.name"
      :key="index"
      />
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

const listOffiles = [
  {
    name: 'pages/do-not-tow.vue'
  },
  {
    name: 'insert'
  },{
    name: 'insert'
  },{
    name: 'insert'
  },{
    name: 'insert'
  },{
    name: 'insert'
  },{
    name: 'insert'
  },{
    name: 'insert'
  },{
    name: 'insert'
  },{
    name: 'insert'
  },{
    name: 'insert'
  },{
    name: 'insert'
  },{
    name: 'insert'
  },{
    name: 'insert'
  },{
    name: 'insert'
  },{
    name: 'insert'
  },{
    name: 'insert'
  },{
    name: 'insert'
  },{
    name: 'insert'
  }
]
export default {
  name: 'app',
  components: {
    HelloWorld
  },
  data () {
    return {
      listOffiles
    }
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
  margin-top: 60px;
}
</style>
