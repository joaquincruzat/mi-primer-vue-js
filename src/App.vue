<template>
 <div>
   <h1 class="text-center mt-5">Tabla de Usuario</h1>
   <table class="table table-striped mt-3">
     <thead>
       <tr>
         <th>#</th>
         <th>Nombre</th>
         <th>Apellido</th>
         <th>RUN</th>
         <th>Fecha de nacimiento</th>
         <th>Edad</th>
       </tr>
     </thead>
     <tbody>
       <tr>
         <td>{{usuario1.numero}}</td>
         <td>{{usuario1.nombre}}</td>
         <td>{{usuario1.apellido}}</td>
         <td>{{usuario1.RUN}}</td>
         <td>{{usuario1.fechaDeNacimiento}}</td>
         <td>{{usuario1.edad}}</td>
       </tr>
       <tr>
         <td>{{usuario2.numero}}</td>
         <td>{{usuario2.nombre}}</td>
         <td>{{usuario2.apellido}}</td>
         <td>{{usuario2.RUN}}</td>
         <td>{{usuario2.fechaDeNacimiento}}</td>
         <td>{{usuario2.edad}}</td>
       </tr>
       <tr>
         <td>{{usuario3.numero}}</td>
         <td>{{usuario3.nombre}}</td>
         <td>{{usuario3.apellido}}</td>
         <td>{{usuario3.RUN}}</td>
         <td>{{usuario3.fechaDeNacimiento}}</td>
         <td>{{usuario3.edad}}</td>
       </tr>
     </tbody>
   </table>
 </div>
</template>

<script>

export default {
  name: 'App',
data: ()=> ({
  usuario1: {
  numero: "1",
  nombre: "Juanito",
  apellido: "Pérez",
  RUN: "19.321.456-7",
  fechaDeNacimiento: "05 de Marzo de 1992",
  edad: "30",
  },
  usuario2: {
  numero: "2",
  nombre: "María",
  apellido: "González",
  RUN: "5.321.456-7",
  fechaDeNacimiento: "15 de Junio 1977",
  edad: "44",
  },
  usuario3: {
  numero: "3",
  nombre: "Viviana",
  apellido: "Tapia",
  RUN: "20.123.555-8",
  fechaDeNacimiento: "21 de Septiembre de 2005",
  edad: "16",
  }

}),
}
</script>

<style>
</style>
