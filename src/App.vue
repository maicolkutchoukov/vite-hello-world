

<script>
// 1) Importazione AppTitle da components
import AppTitle from './components/AppTitle.vue'
export default {
    data() {
        return { 
            title : 'Hello World!' 
        }
    },
    // 2) Dichiarazione AppTitle in components
    components: {
        AppTitle
    }
};
      
</script>

<template>
    <div>
      
        <h1>
            {{ title }}
        </h1>
        <!-- Utilizzo AppTitle -->
        <AppTitle/>
  </div>
</template>

<style scoped>
h1{
    text-align: center;
    font-size: 3rem;
    color: blue;
    background-color: red;
}
</style>
