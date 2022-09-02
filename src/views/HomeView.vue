<template>
  <div class="home">
    <img alt="chain links" src="../assets/links.png">
    <HelloWorld msg="Some most useful links"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'HomeView',
  components: {
    HelloWorld
  }
}
</script>
