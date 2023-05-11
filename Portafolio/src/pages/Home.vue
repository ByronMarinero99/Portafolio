<script setup lang="ts">
import { RouterLink } from 'vue-router';

import Layaout from '../components/Layaout.vue';
</script>
<template>
    <Layaout>

        <header>
            <section class="text-white-600 body-font bg   bg-[#08f] ">
                <div class="container mx-auto flex px- py-24 md:flex-row flex-col items-center ">
                    <div class="lg:flex-grow md:w-1/2 lg:pr-24 md:pr-16 flex flex-col md:items-start md:text-left mb-16 md:mb-0 items-center text-center ">
                    <h1 class="title-font sm:text-3xl text-3xl mb-4 font-medium text-white "> ¡Bienvenido! </h1>
                    <h1 class="title-font sm:text-5xl text-5xl mb-4 font-medium text-white">Soy Byron Marinero
                    </h1>
                    <p class="mb-8 leading-relaxed text-white">Frond-End Developer | UX disigner </p>
                    <div class="flex justify-center">
                        <div class="flex justify-center">
                        <button class="inline-flex text-white bg-blue-700 border-0 py-2 px-6 focus:outline-none hover:bg-blue-900 rounded text-lg">
                            <RouterLink to="/about">Ver mas</RouterLink>
                        </button>
                        </div>
                    </div>
                    </div>
                    <div class="lg:max-w-lg lg:w-full md:w-1/2 w-5/6">
                    <img class="object-cover object-center rounded animate-bounce" src="../assets/img/Web Developer_Monochromatic.svg">
                    </div>
                </div>
            </section>
            
        </header>
        <body>
            <div style="height: 150px; overflow: hidden;" ><svg viewBox="0 0 500 150" preserveAspectRatio="none" style="height: 100%; width: 100%;"><path d="M-25.11,2.48 C206.83,159.38 265.52,-63.63 526.80,74.52 L504.79,-8.36 L-4.22,-9.36 Z" style="stroke: none; fill: #08f;"></path></svg></div>
            

            <h1 class="text-center text-6xl">Proyectos</h1>
            <section class="text-gray-600 body-font bg-white">
                <div class="container px-5 py-24 mx-auto flex flex-wrap">
                    <div class="flex flex-wrap md:-m-2 -m-1">
                        <div class="flex flex-wrap w-1/2">
                        <div class="md:p-2 p-1 w-1/2">
                            <img alt="gallery" class="w-full object-cover h-full object-center block" src="../assets/img/tropiko.jpeg">
                        </div>
                        <div class="md:p-2 p-1 w-1/2">
                            <img alt="gallery" class="w-full object-cover h-full object-center block" src="../assets/img/multishop.jpeg">
                        </div>
                        <div class="md:p-2 p-1 w-full">
                            <img alt="gallery" class="w-full h-full object-cover object-center block" src="../assets/img/multishop.jpeg">
                        </div>
                        </div>
                        <div class="flex flex-wrap w-1/2">
                        <div class="md:p-2 p-1 w-full">
                            <img alt="gallery" class="w-full h-full object-cover object-center block" src="../assets/img/foodhut.jpeg">
                        </div>
                        <div class="md:p-2 p-1 w-1/2">
                            <img alt="gallery" class="w-full object-cover h-full object-center block" src="../assets/img/spa-center.jpeg">
                        </div>
                        <div class="md:p-2 p-1 w-1/2">
                            <img alt="gallery" class="w-full object-cover h-full object-center block" src="../assets/img/webwing.jpeg">
                        </div>
                        </div>
                    </div>
                </div>
            </section>
        </body>

    </Layaout>


</template>