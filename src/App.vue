<script>
/* 
Per importare ed utilizzare un componente dentro ad un altro devo SEMPRE seguire 3 passi:
1. Importazione del componente
2. Dichiarazione del componente
3. Utilizzo del componente
*/

//1. Importazione del componente

export default {
  data() {
    return { 
      message: 'Hello World!'
    }
  }
}
</script>

<template>
  <div>
    <h1>
      {{ message }}
    </h1>
  </div>
</template>

<style scoped>
</style>
