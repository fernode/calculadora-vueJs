<template>
  <div class="calculator"></div>
</template>

<script>
export default {};
</script>

<style scoped>
.calculator {
  grid-template-columns: repeat(4, 1fr);
  grid-auto-rows: minmax(50px, auto);
}
</style>