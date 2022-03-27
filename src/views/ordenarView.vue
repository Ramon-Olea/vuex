
<template>

  <div class="collapse" id="navbarToggleExternalContent">
      <div class="bg-dark p-4">
        <h5 class="text-white h4">Sucursal en Huixquilucan.

          Ponemos a su disposición la dirección y el teléfono en Huixquilucan. Centro Urbano San Fernando S/N, Lote 10,
          Mz. 2, Colonia la Herradura, Local 10., (01 32455) 5293241 8106.</h5>
      </div>
    </div> <nav class="navbar navbar-dark bg-dark">
      <div class="container-fluid">
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse"
          data-bs-target="#navbarToggleExternalContent" aria-controls="navbarToggleExternalContent"
          aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <h1 style="color: aliceblue;">PASTELERIA CORAZONE</h1>
        <ul class="nav nav-pills mb-3" id="pills-tab" role="tablist">
          <li class="nav-item" role="presentation">
           
                   <router-link to="./">INICIO</router-link>
          </li>
          <li class="nav-item" role="presentation">
         
                   <router-link to="/about">PASTELES</router-link>
          </li>
          <li class="nav-item" role="presentation">
             <router-link to="/ordenar">ORDENAR</router-link>

          </li>
        </ul>
      </div>
    </nav>
   





        <div class="container">
          <div class="row">
            <div class="col-sm">
            </div>
            <div class="col-sm">
              <form>
                <div class="form-group">
                  <label for="exampleInputEmail1">NOMBRE</label>
                  <input type="text" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp"
                    placeholder="Enter email">

                </div>
                <div class="form-group">
                  <label for="exampleInputEmail1">TELEFONO</label>
                  <input type="number" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp"
                    placeholder="Enter email">

                </div>
                <div class="form-group">
                  <label for="exampleInputEmail1">CORREO</label>
                  <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp"
                    placeholder="Enter email">

                </div>
                <div class="form-group">
                  <label for="exampleInputEmail1">Descripción general</label>
                  <textarea name="" id="" cols="50" rows="10"></textarea>
                </div>

                <button type="submit" class="btn btn-primary">ENVIAR</button>
              </form>
            </div>
            <div class="col-sm">
            </div>
          </div>
        </div>

      
</template>
<script>
import HelloWorld from '@/components/HelloWorld.vue'

import '@popperjs/core';
import 'bootstrap/dist/css/bootstrap.css'
import 'bootstrap-vue/dist/bootstrap-vue.css'
const $ = require('jquery')
// Lo declaramos globalmente
window.$ = $
export default {
  name: 'ordenarView',
  props: {
    msg: String
  }
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
