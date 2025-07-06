<template>
  <div class="box">
    <h1>hello world</h1>
    <Person />
  </div>
</template>



<script setup lang="ts">
import Person from "./components/Person.vue";
  // export default {
  //   name: 'App',
  //   components: {
  //     Person
  //   }
  // }
</script>

<style scoped>
.box {
  background-color: red;
  box-shadow: 0 0 10px;
  border-radius: 10px;
  padding: 20px;
}
</style>
