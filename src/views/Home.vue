<template>
  <div class="home">
    <img alt="Vue 3 Twitter Clone logo" src="../assets/twitter.png">
    <HelloWorld msg="Vue 3 Twitter Clone"/>
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
