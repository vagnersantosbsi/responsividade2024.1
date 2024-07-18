<template>
  <div id="app">
    <form id="app-form">
      <input type="text" v-model="input_name" placeholder="Digite seu Nome">
      <input type="submit" value="Enviar" v-on:click="submitForm">
    </form>
    <p>O meu nome é:{{ name }}</p>
    <p>data binding: {{ input_name }}</p>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
input {
  background-color: black;
  color: beige;
  width: 20%;
  height: 50px;
  font-size: 20px;
}

bemvindo {
  color: green;
  font-size: 30px;
}

h3 {
  margin: 40px 0 0;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}
</style>
