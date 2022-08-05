<template>
  <div class="container">
    <div class="form-todo form-group">
      <p>
        <input placeholder="nome" type="text" name="author" class="form-control" v-model="name" />
      </p>
      <p>
        <textarea placeholder="comentário" type="text" name="author" class="form-control" v-model="message" ></textarea>
      </p>
      <button type="submit" class="btn btn-primary">Comentar</button>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  },
  data () {
   return {
        name: '',
        message: ''
      }
  }
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
