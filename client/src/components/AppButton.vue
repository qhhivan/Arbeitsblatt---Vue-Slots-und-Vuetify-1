<template>
  <div>
    <button><slot class="slot-style"/></button>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
button {
  padding: 5px;
  border: 1px solid black;
  border-radius: 10px;
  text-transform: uppercase;
  width: 150px;
  height: 185px;
  background-color: white;
}


</style>
