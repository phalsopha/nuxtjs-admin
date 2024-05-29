<template>
  <div>
    <h2>Hello world </h2>
    <button @click="increment"> Increment</button>
    <button @click="decrement"> decrement</button>
    <p>{{count}}</p>
  </div>
</template>


<script setup>
const count =ref(0)
function increment() {
  count.value++;
  }
function decrement() {
  count.value--;
  }
</script>

<style lang="scss" scoped>

</style>
