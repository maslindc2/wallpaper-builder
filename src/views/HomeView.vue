<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HomePage />
  </div>
</template>

<script>
// @ is an alias to /src
import HomePage from '@/components/HomePage.vue'

export default {
  name: 'HomeView',
  components: {
    HomePage
  }
}
</script>
<style>
ul {
  list-style-type: none;
  padding: 0;
}
img {
  width: 250px;
}
</style>
