<template>
  <div class="">
    <h1></h1>
    <p>
    </p>
    <h2>Analisis rapido de audios</h2>
    <ul>
      <input type="text" name="" placeholder="Nombre de script o camapaña" style="width:500px ;">
    <br/>

<select name="tipo" id="tipo" style="width:500px ;">
  <option value="">Seleccione tipo de contacto (directo o indirecto)</option>
  <option value="Directoo">Directo</option>
  <option value="Indirecto">Indirecto</option>
  



</select> 
      
    </ul>
    
    <input type="button" value="Agregar Categoria">  <input type="button" value="Siguiente">
    

    
    <ul>
      
    </ul>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',


}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
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
