<template>
  <ListaComentario></ListaComentario>
</template>

<script>
import ListaComentario from './components/ListaComentario.vue'

export default {
  name: 'App',
  components: {
    ListaComentario
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
