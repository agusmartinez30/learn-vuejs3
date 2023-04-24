//logica
<script setup>
  const name = "mundo"
  const styleColor = "color: yellow"
</script>

<template>
  <h1>Hola {{ name }}</h1>
  <h2 :style="styleColor">SOY AZUL</h2>
</template>

<style>
h1 {
  color: red;
}
</style>