<template>
  <!-- SINGLE FILE COMPONENT -->
  <div class="container">
    <h1>Hello, world!</h1>
    <h2>{{ nome }}</h2>
    <input type="text" v-model="nome" />
  </div>
</template>

<script>
export default {
  data(){
    return { 
      nome: "Bruno costa",
      usuario: {
        idade: 24,
        email: "email@email.com"
      }
    }
  }
}
</script>

<style>
.container {
  width: 100vw;
  height: 100vh;
  background-color: rgb(244, 129, 129);
}
</style>
