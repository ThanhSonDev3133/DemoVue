<template>
  <div id="app">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <MenuWorld/>
    <Contact/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import MenuWorld from './components/MenuWorld.vue'
import Contact from './components/Contact.vue'
export default {
  name: 'App',
  components: {
    HelloWorld,
    MenuWorld,
    Contact
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
</style>
