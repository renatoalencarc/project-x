<script setup lang="ts">

defineProps({
  
})

</script>

<template>
<div class="nav">
  <button><span><Routerlink to="/github">Github</Routerlink></span></button>
  <button>Projetos</button>
  <button id="home">Home</button>
  <button>Acadêmico</button>
  <button>Contato</button>
</div>

</template>

<style scoped>
 .nav {
 background-color: black;
 width: 100vw;
 text-align: center;
 margin: 10px;
 padding: 1px;
}

</style>
