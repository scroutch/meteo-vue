<template>
  <div id="app">
    <meteo></meteo>
  </div>
</template>

<script>

import Meteo from './components/Meteo'

export default {
  name: 'App',
  components: {
    'meteo': Meteo
  }
}
</script>

<style>
    body {
      background: #43c6ac;
      background: linear-gradient(to right, #f8ffae, #43c6ac)
    }
</style>
