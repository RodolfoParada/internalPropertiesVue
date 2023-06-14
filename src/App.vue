<template>
  <InternalProperties name="Félix" propiedadquenoestaenprops="esta" />
</template>

<script>
import InternalProperties from './components/InternalProperties.vue'

export default {
  name: 'App',
  components: {
    InternalProperties
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
