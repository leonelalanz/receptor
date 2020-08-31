
<!-- Contenido html / Html content -->
<template>
  <div id="app">
    <img src="./assets/QuashBlancorecPng.png" width="300px" height="80px">
    <h1>{{ msg }}</h1>
    <ul>
      <i class="fa fa-folder-open-o" aria-hidden="true"></i>
       <input type="file" accept=".csv, .xlsx, .xls" @change="onFileSelected" name="myfile">
    </ul>
  </div>
</template>


<!-- Lógica (variables,funciones,etc) / Logic (variables, functions, etc) -->
<script>
export default {
  name: 'app',
  data () {
    return {
      msg: 'Seleccione un Archivo'
    }
  }
}
</script>


<!-- Estilos / Styles -->
<style lang="scss">
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale; 
  text-align: center;
  color: #2c3e50;

}

h1, h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
  }


body{
background-color:#000023;
background-repeat:no-repeat;
align:center;
}


img {
margin-top:150px;
}
</style>
