<template>
  <div id="nav">
    <router-link>
      <img src="" id="logo" />
    </router-link>
    <router-link to="/">Home</router-link> |
    <router-link to="/pedidos">Pedidos</router-link>
  </div>
</template>

<script>
export default {
  name: "NavbarComponent",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped></style>
