<template>
    <div class="fixed left-16 bottom-4 w-11/12 border-2 rounded-lg  bg-[#303032]">
    <div class="flex justify-between p-4">

        <img v-if="active == 0" class="w-10 cursor-pointer" src="../assets/images/footer/ho_ho1.png" />
        <img @click="changeActive(0)" v-else class="w-10 cursor-pointer" src="../assets/images/footer/ho_ho2.png" />




        <img v-if="active == 1"  class="w-10 cursor-pointer" src="../assets/images/footer/ho_ac1.png" />
        <img @click="changeActive(1)" v-else  class="w-10 cursor-pointer" src="../assets/images/footer/ho_ac2.png" />

        <img v-if="active == 2"  class="w-10 cursor-pointer" src="../assets/images/footer/ho_wa1.png" />
        <img @click="changeActive(2)" v-else  class="w-10 cursor-pointer" src="../assets/images/footer/ho_wa2.png" />


        <img v-if="active == 3" class="w-10 cursor-pointer" src="../assets/images/footer/ho_co1.png" />
        <img @click="changeActive(3)" v-else  class="w-10 cursor-pointer" src="../assets/images/footer/ho_co2.png" />


        <img  v-if="active == 4" class="w-10 cursor-pointer" src="../assets/images/footer/ho_my1.png" />
        <img @click="changeActive(4)" v-else class="w-10 cursor-pointer" src="../assets/images/footer/ho_my2.png" />
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