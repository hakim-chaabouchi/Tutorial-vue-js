<template>
    <div>
           <div :class="class_name">Hellow World  {{ p }} et {{ d [2]}}</div>
           <SecondVue msg="this is the msg of"/>
           <button @click="func_1">btn</button>
    </div>
</template>

<script setup>
    import SecondVue from './Second.vue'


   const p = 'paragraphe'
   const d = [1, 2,3]
   const func_1 = () => {
    console.log(' this is func_1 ()');
   }
   const class_name= 'class1'
   
 

</script>

<style scoped>
.class1 {
    color: brown;
    background-color: aquamarine;
   
}

</style>