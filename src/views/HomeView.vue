<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <Contador />
    <Cuadrado />
    <Botones />
  </div>
</template>

<script>
import Contador from "../components/Contador.vue";
import Cuadrado from "../components/Cuadrado.vue";
import Botones from "../components/Botones.vue";

export default {
  name: "HomeView",
  components: {
    Contador,
    Cuadrado,
    Botones,
  },
};
</script>
