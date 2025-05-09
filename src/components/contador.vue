<template>
<h1>hola mundo</h1>
<p>{{ contador }}</p>
<button @click="incrementar">incrementar</button>
<button @click="decrementar">Decrementar</button>
</template>

<script setup>
import { ref } from 'vue'

const contador=ref(0);



const incrementar=() =>{
  contador.value++;
}

const decrementar=() =>{
  contador.value--;
}
</script>

<style>

</style>
