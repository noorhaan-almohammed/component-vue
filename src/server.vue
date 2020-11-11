<template>
 <div id="app">
    <p>server status : {{status}}</p>
    <button @click='changeStatus'>change</button>
    <hr>
 </div>
</template>

<script>
     export default {
       data : function (){
       return { status : 'cretical'}
       },
       methods : {
         changeStatus(){
           this.status ="Normal"
         }
       }
     }
</script>
<style>
   p{
     color: rgb(105, 24, 112);
   }
   button{
     background: rgb(231, 197, 123);
     color:rgb(158, 144, 19);
     border-color: rgb(175, 173, 21);
   }
   #app{
     text-align: center;
   }
</style>
