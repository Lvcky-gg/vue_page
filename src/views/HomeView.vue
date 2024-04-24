<script setup>

</script>

<template>
  <div class="test" >
    <p v-for="i in 100">Hello</p>

   
  </div>

</template>
<style scoped>
  .test {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100%;
  width: 100%;
  z-index: 1;
  position: absolute;
  background-color: rgba(71, 71, 71, 0.377);
  flex-direction: column;
  justify-content: center;
  align-items: center;
  overflow-y: scroll;
  }
</style>
