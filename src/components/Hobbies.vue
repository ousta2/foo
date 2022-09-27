<template>
    <div class="flex justify-start bg-[#303032] mt-4 p-10 rounded-xl">

        <div class="flex flex-col justify-between">
            <img v-if="active == 0"  class="w-24 h-24 cursor-pointer" src="../assets/images/hobbies/ho_li13x.png" />
            <img @click="changeActive(0)" v-else class="w-24 h-24 cursor-pointer" src="../assets/images/hobbies/ho_li23x.png" />


            <img  v-if="active == 1" class="w-24 h-24 cursor-pointer" src="../assets/images/hobbies/ho_sp13x.png" />
            <img @click="changeActive(1)" v-else class="w-24 h-24 cursor-pointer" src="../assets/images/hobbies/ho_sp23x.png" />
            
            <img v-if="active == 2" class="w-24 h-24 cursor-pointer" src="../assets/images/hobbies/ho_lo13x.png" />
            <img @click="changeActive(2)" v-else class="w-24 h-24 cursor-pointer" src="../assets/images/hobbies/ho_lo23x.png" />


            <img  v-if="active == 3" class="w-24 h-24 cursor-pointer" src="../assets/images/hobbies/ho_po13x.png" />
            <img @click="changeActive(3)" v-else class="w-24 h-24 cursor-pointer" src="../assets/images/hobbies/ho_po23x.png" />


            <img v-if="active == 4" class="w-24 h-24 cursor-pointer" src="../assets/images/hobbies/ho_ga13x.png" />
            <img @click="changeActive(4)" v-else class="w-24 h-24 cursor-pointer" src="../assets/images/hobbies/ho_ga23x.png" />
        </div>


        <div  class="flex flex-col  ml-20 justify-between  w-2/3">
            <img class="w-full mb-10" src="../assets/images/hobbies/game-image.dcbb90ad.png" />
            <img class="w-full mb-10" src="../assets/images/hobbies/game-image-2.000b53bd.png" />
            <img class="w-full" src="../assets/images/hobbies/game-image.dcbb90ad.png" />
        </div>
    </div>
</template>

<script setup>
import {ref } from "vue";
const active = ref(0);

const changeActive = (a) => {
    active.value = a;
}

</script>

<style scoped>

</style>