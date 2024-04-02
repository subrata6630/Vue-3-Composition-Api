<script setup>

let msg = "Hello world!";

let dynamicId ="2"

let isButonDisabled = true

</script>





<template>

<!-- Print v-html -->
<!--Print {{ msg }} -->


  <div v-html="msg"></div>


<!-- Dynamic id bind. Please Check inscpect  element to see the result-->

  <div v-bind:id ="dynamicId">Dynamic id :  {{ dynamicId}} </div>

<!-- Another Style  of binding data with attribute (Short hand bind) -->

<div :id ="dynamicId">Dynamic id :  {{ dynamicId}} </div>


<button :disabled="isButonDisabled">Click me!</button>


  
</template>

<style scoped>


</style>
