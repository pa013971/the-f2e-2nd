<template>
  <div class="home">
    <div id="nav">
      <router-link to="/">首頁</router-link> |
      <router-link to="/freecell">新接龍</router-link>
    </div>
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld
  }
}
</script>
