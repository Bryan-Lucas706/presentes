<script setup>
 import { ref } from 'vue'

 const count = ref(0)
</script>


<template>
  <h1>Teste de github pages</h1>
  <p>Contador: {{ count }}</p>
  <button @click="count++">Incrementar</button>
</template>

<style scoped></style>
