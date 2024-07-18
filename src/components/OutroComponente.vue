<template>
    <div id="app">
        <form id="app-form">
            <input type="text" v-model="input_name" placeholder="Digite seu Nome">
            <input type="submit" value="Enviar" v-on:click="submitForm">
        </form>
        <p>O meu nome é:{{ name }}</p>
        <p>data binding: {{ input_name }}</p>
    </div>F
</template>

<script>
export default {
    name: 'OutroComponente',
    props: {
        msg: String
    }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped></style>