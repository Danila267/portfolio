<template>
  <Header />
  <router-view/>
</template>

<script>
import Header from './components/Header.vue';

export default {
  name: 'App',
  components: { Header, }
}

</script>

<style lang="scss">
* {
  padding: 0;
  margin: 0;
  width: 100%;
}

body {
  background-color: #323841;
}


</style>
