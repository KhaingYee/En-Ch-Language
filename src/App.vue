<template>
  <div id="app">
    <LocaleSwitcher />
    <p>{{ $t('main.welcome', {company: 'Lokalise'}) }}</p>
  </div>
</template>

<script>
import LocaleSwitcher from './components/LocaleSwitcher.vue'

export default {
  name: 'App',
  data() {
    return {
    }
  },
  components: {
    LocaleSwitcher
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
