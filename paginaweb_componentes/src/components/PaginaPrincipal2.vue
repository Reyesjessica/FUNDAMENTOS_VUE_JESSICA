<script setup>
import encabezado from './encabezado.vue';
import Pmenu from './Pmenu.vue';
import carosel from './carosel.vue';
import cardPostre from './cardPostre.vue';
import seccion from './seccion.vue';
import CardOfertas from './CardOfertas.vue';
import formulario from './formulario.vue';
</script>

<template>
   <!-- Encabezado -->
<encabezado/>
<!-- Menu  -->
 <Pmenu/>

  <!-- Carosel -->
 <carosel/>
  <!-- Card de postre -->
  <cardPostre/>
      <!-- seccion de parrafos y textos -->
     <seccion/>
  <!-- Card de ofertas -->
  <CardOfertas/>
  <!-- Formulario -->
  <formulario/>
  <!-- Pie de pagina  -->
  <footer style="background-color: black; color:#fff;" class="text-center py-3 ">@DWB-Todos los derechos reservados
</footer>



 
</template>

<style scoped>


</style>
