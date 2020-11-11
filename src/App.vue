<template>
  <div>
    <head_page></head_page>
    <hr>
    <body_page></body_page>
    <hr>
    <footer_page></footer_page>
  </div>

</template>

<script>
import Head from './Header.vue'
import footer from './footer.vue'
import body from './body.vue'
export default {
  components:{
    head_page : Head,
    footer_page : footer,
    body_page : body
  }
}
</script>

<style></style>
