<template>
<div class="ss">
  <server_status class="ss" v-for="server in 5"></server_status>
</div>
</template>

<script>
import serverStatus from './server.vue';
export default {
     components :{
       server_status : serverStatus
     }
}
</script>
<style >

   .ss{
    background: rgb(241, 220, 122);
    padding: 10px;
  }
</style>
