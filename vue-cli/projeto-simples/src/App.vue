<template>
  <div id="app">
      {{titulo}}
  </div>
</template>

<script>
export default {
   data: function(){
      return {
         titulo: 'Olá esse é meu primeiro VUE-CLI'
      }
   }
}
</script>

<style>
    #app {
       background-color: aqua;
    }
</style>
