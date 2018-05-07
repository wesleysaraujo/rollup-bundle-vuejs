<template>
  <div class="container-msg">
    {{ msg }}
  </div>
</template>

<script>
import Todo from './components/todo/Main.vue'

export default {
  data () {
    return {
      msg: 'ToDo - Lista de Tarefas'
    }
  },
  components: {
    Todo
  }
}
</script>

<style>
.container-msg{
  background: #0988a0;
  padding: 10px;
  color: #ffffff;
}
</style>
