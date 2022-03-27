<template>
  <div class="home">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
// @ is an alias to /src
import '@popperjs/core';


import HelloWorld from '@/components/HelloWorld.vue'
import 'bootstrap/dist/css/bootstrap.css'
import 'bootstrap-vue/dist/bootstrap-vue.css'
const $ = require('jquery')
// Lo declaramos globalmente
window.$ = $
export default {
  name: 'HomeView',
  components: {
    HelloWorld
  },
  
}

</script>
