<template>
  <div class="mt-8">
    <div class="mt-2">
      <h2
        class="mb-2 text-xl text-gray-700 font-bold dark:text-blue-200 capitalize"
      >
        Frontend
      </h2>

      <ul class="flex flex-wrap gap-4 items-center">
        <li class="flex items-center"> 
        <Typescript class="h-10 w-10 rounded-sm drop-shadow-sm"></Typescript>
        </li>
        <li class="flex items-center">
        <Angular class="h-10 w-10 rounded-sm drop-shadow-sm"></Angular>
        </li>
       
        <li class="flex items-center">
          <Javascript class="h-10 w-10"></Javascript>
        </li>
           <li class="flex items-center">
          <React class="h-10 w-10"></React>
        </li>
         <li class="flex items-center">
          <Sass class="h-10 w-10 rounded-sm drop-shadow-sm"></Sass>
        </li>
      </ul>
    </div>
    <div class="mt-4">
      <h2
        class="mb-2 text-xl text-gray-700 font-bold dark:text-blue-200 capitalize"
      >
        Backend
      </h2>
      <ul class="mb-6 flex flex-wrap gap-4">
        <li class="flex items-center">
          <Node class="h-10 w-10"></Node>
        </li>
          <li class="flex items-center">
          <Pgsql class="h-10 w-10"></Pgsql>
        </li>
          <li class="flex items-center">
          <Nest class="h-10 w-10"></Nest>
        </li>
      </ul>
    </div>
  </div>
</template>

<script>
import Javascript from "../assets/devicon/javascript.svg?inline";
import Html from "../assets/devicon/html.svg?inline";
import Sass from "../assets/devicon/sass.svg?inline";
import Vuejs from "../assets/devicon/vuejs.svg?inline";
import Angular from "../assets/devicon/angular.svg?inline";
import Nuxt from "../assets/devicon/nuxt.svg?inline";
import Node from "../assets/devicon/node.svg?inline";
import Typescript from "../assets/devicon/typescript.svg?inline";
import Pgsql from "../assets/devicon/postgresql.svg?inline";
import Nest from "../assets/devicon/nest.svg?inline";
import React from "../assets/devicon/react.svg?inline";
export default {
  components: {
    Javascript,
    Html,
    Sass,
    Vuejs,  
    Angular,
    Nuxt,
    Pgsql,
    Typescript, 
    Node,
    React,
    Nest
  },
};
</script>
