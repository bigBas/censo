<template>
  <div id="app">
    <Header />
      <router-view></router-view>
    <Footer />
  </div>
</template>

<script>
import Header from './components/Header'
import Footer from './components/Footer'

import Vue from 'vue'

import 'bootstrap/dist/css/bootstrap.css'

export default {
  name: 'app',
  components: {
        Header,
        Footer
    },
}
</script>

<style scoped>

#app {
  
}

</style>
