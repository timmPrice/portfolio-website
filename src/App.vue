<template>
    <div id = "app">
        <LOGO />
        <FOOT />
    </div>
</template>

<script>
import LOGO from './components/Logo.vue'
import FOOT from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    LOGO,
    FOOT,
  }
}
</script>

<style>
    #app {
        margin-left: 3%;
        margin-top: 5%;
    }
</style>
