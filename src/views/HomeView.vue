<template>
  <Navbar></Navbar>
  <router-view></router-view>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import Navbar from '@/components/FrontNavbar.vue'

export default {
  name: 'HomeView',
  components: {
    Navbar
  }
}
</script>
