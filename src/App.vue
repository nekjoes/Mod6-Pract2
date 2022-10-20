<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome tos Your Vue.js App"/> -->
  <div>
    <BarraX/>
    <ProductoX/>
    <ProductoY/>
    <FootX />
  </div>
  
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import BarraX from './components/Barra1.vue'
import ProductoX from './components/Producto.vue'
import ProductoY from './components/ProductRelac.vue'
import FootX from './components/Foot.vue'

// export default {
//   name: 'App',
//   components: {
//     HelloWorld
//   }
// }
export default {
  name: 'App',
  components: {
    BarraX,
    ProductoX,
    ProductoY,
    FootX
  }
}
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
