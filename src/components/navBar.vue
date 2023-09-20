<template>
    <v-app-bar app color="#323B33" dark flat class="px-12" >
      <v-btn >
        <v-icon color="red" left class="mr-2">fas fa-computer</v-icon> DVGM
      </v-btn>
      
      <v-spacer></v-spacer>
      <v-btn text @click="scroll('home')" class="text-red">Inicio</v-btn>
      <v-btn text @click="scroll('about')"  >About Me</v-btn>
      <v-btn text @click="scroll('projects')"  >Proyectos</v-btn>
      <v-btn text @click="scroll('hireN')"  >Contratame</v-btn>
      <v-btn text @click="scroll('contact')"  > Contacto</v-btn>
    </v-app-bar>
  </template>
  
  <script>
  export default {
    methods: {
      scroll(refName) {
        const element = document.getElementById(refName);
        element.scrollIntoView({ behavior: "smooth" });
      },
    },
  };

  </script>

<style>

</style>
