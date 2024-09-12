<script>
/* 
Per importare ed utilizzare un componente dentro ad un altro devo SEMPRE seguire 3 passi:
1. Importazione del componente
2. Dichiarazione del componente
3. Utilizzo del componente
*/

import AppTitle from './components/AppTitle.vue';

export default {
  data() {
    return { 
      message: ''
    }
  },
  components: {
    AppTitle
  }
}
</script>

<template>
  <AppTitle />
</template>

<style scoped>
</style>
