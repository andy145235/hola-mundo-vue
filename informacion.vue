<template>
<script src="https://cdn.jsdelivr.net/npm/vue@2.5.16/dist/vue.js"></script>

  <div id="informacion">
    <h2>BANCO BNB</h2>
    <img alt="Vue logo" src="https://play-lh.googleusercontent.com/EDhozWhNCLv4mf_lSQxEaOkAYPTwx4Y-R28PQEqnYi-CNxH5aE316KKpulJQU5LXVilZ" />
  </div>
  <center>
  <p style="width:200px" >Banco Nacional de Bolivia SA es un banco e institución financiera boliviana con sede en Sucre, Bolivia. Fundado en 1871, es uno de los bancos más antiguos de Bolivia. También es el segundo banco más grande del país por activos totales.</p>
  </center>
    <div class="center">
      <vs-button
        border
        :active="active == 0"
        @click="active = 0"
      >
        FORMULARIO
      </vs-button>
    </div>
</template>

<script>
export default {
  name: 'informacion',
  components: {},
};
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