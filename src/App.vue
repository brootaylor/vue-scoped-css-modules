<template>
  <div id="app">
    <Header />
    <router-view />
  </div>
</template>

<script>
import Header from './components/layout/Header';

export default {
  name:"app",
  components: {
    Header
  }
}
</script>

<style lang="scss">
  * {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
  }

  html {
    font-family: Arial, Helvetica, sans-serif;
    font-size: 62.5%;
    line-height: 1.4;
  }

  body {
    font-size: 1.6rem;
  }
</style>
