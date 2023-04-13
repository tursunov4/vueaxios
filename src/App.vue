<template>
  <div>
    <TableApp/>
    <hr class="m-5">
   <PostsApp/>
  </div>
</template>

<script setup>
import TableApp from './components/TableApp/TableApp.vue';
import PostsApp from './components/PostsApp/PostsApp.vue';
</script>

<style  scoped>
  h1{
    color: red;
  }
</style>