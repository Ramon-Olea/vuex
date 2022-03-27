
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
              <div class="card" style="width:400px">
                <img class="card-img-top" src="../../pastel2.jpeg" alt="Card image">
                <div class="card-body">
                  <h4 class="card-title">PASTEL LUNETAS</h4>
                  <p class="card-text">$ 450</p>
                  <a href="#" class="btn btn-primary">ORDENAR</a>
                </div>
              </div>
            </div>
            <div class="col-sm">
              <div class="card" style="width:400px">
                <img class="card-img-top" src="../../pastel4.jpeg" alt="Card image">
                <div class="card-body">
                  <h4 class="card-title">PASTEL ESPECIAL</h4>
                  <p class="card-text">$ 700 </p>
                  <a href="#" class="btn btn-primary">ORDENAR</a>
                </div>
              </div>
            </div>
            <div class="col-sm">
              <div class="card" style="width:400px">
                <img class="card-img-top" src="../../pastel6.jpeg" alt="Card image">
                <div class="card-body">
                  <h4 class="card-title">PASTEL BOMBON</h4>
                  <p class="card-text">$ 600</p>
                  <a href="#" class="btn btn-primary">ORDENAR</a>
                </div>
              </div>
            </div>
          </div>
        </div>
        <BR></BR>
        <hr>
        <div class="container">
          <div class="row">
            <div class="col-sm">
              <div class="card" style="width:400px">
                <img class="card-img-top" src="../../pastel1.png" alt="Card image">
                <div class="card-body">
                  <h4 class="card-title">PASTEL CHOCOLK</h4>
                  <p class="card-text">$ 400</p>
                  <a href="#" class="btn btn-primary">ORDENAR</a>
                </div>
              </div>
            </div>
            <div class="col-sm">
              <div class="card" style="width:400px">
                <img class="card-img-top" src="../../pasltel2.jpeg" alt="Card image">
                <div class="card-body">
                  <h4 class="card-title">PASTEL FRESA</h4>
                  <p class="card-text">$ 750</p>
                  <a href="#" class="btn btn-primary">ORDENAR</a>
                </div>
              </div>
            </div>
            <div class="col-sm">
              <div class="card" style="width:400px">
                <img class="card-img-top" src="../../pasltel4.jpeg" alt="Card image">
                <div class="card-body">
                  <h4 class="card-title">PASTEL ROSE</h4>
                  <p class="card-text">$ 800</p>
                  <a href="#" class="btn btn-primary">ORDENAR</a>
                </div>
              </div>
            </div>
          </div>
        </div>
        <br>
        <hr><br>
        <h1 class="text-center">INGREDIENTES DE PASTELES</h1>
        <table class="table">
          <thead class="thead-dark">
            <tr>
              <th scope="col">#</th>
              <th scope="col">INGREDIENTES</th>
              <th scope="col">PRECIO</th>
            </tr>
          </thead>
          <tbody>
            <tr>
              <th scope="row">1</th>
              <td>NUBES DE GOLOCINA</td>
              <td> + $10</td>
            </tr>
            <tr>
              <th scope="row">2</th>
              <td>FERRERO</td>
              <td>+ $20</td>
            </tr>
            <tr>
              <th scope="row">3</th>
              <td>FLORES DE AZUCAER</td>
              <td>+30</td>
            </tr>
            <tr>
              <th scope="row">4</th>
              <td>FLORES DE AZUCAE</td>
              <td>+30</td>
            </tr>
            <tr>
              <th scope="row">5</th>
              <td>MARIPOSAS DE AZUCAE</td>
              <td>+20</td>
            </tr>
            <tr>
              <th scope="row">6</th>
              <td>BOMBONES</td>
              <td>+10</td>
            </tr>
            <tr>
              <th scope="row">7</th>
              <td>FRESAS</td>
              <td>+15</td>
            </tr>
            <tr>
              <th scope="row">8</th>
              <td>CHOCOLATES</td>
              <td>+30</td>
            </tr>
          </tbody>
        </table>
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
  name: 'AboutView',
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
