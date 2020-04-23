<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to toko.wang"/>
    <Foot />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import Foot from '@/components/Footer.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld, Foot
  }
}
</script>
