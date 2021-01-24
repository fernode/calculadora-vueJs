<template>
  <div class="calculator">
    <div class="display">0.9898234</div>
    <div class="btn">AC</div>
    <div class="btn">+/-</div>
    <div class="btn">%</div>
    <div class="btn operator">÷</div>
    <div class="btn">7</div>
    <div class="btn">8</div>
    <div class="btn">9</div>
    <div class="btn operator">x</div>
    <div class="btn">4</div>
    <div class="btn">5</div>
    <div class="btn">6</div>
    <div class="btn operator">-</div>
    <div class="btn">1</div>
    <div class="btn">2</div>
    <div class="btn">3</div>
    <div class="btn operator">+</div>
    <div class="btn zero">0</div>
    <div class="btn">.</div>
    <div class="btn operator">=</div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.calculator {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  grid-auto-rows: minmax(50px, auto);
  color: #000000;
  font-size: 40px;
  background: rgb(219, 219, 219);
  width: 400px;
  margin: 0 auto;
}

.display {
  color: white;
  padding-right: 5px;
  text-align: right;
  background: rgb(45, 46, 124);
  grid-column: 1/5;
}

.zero {
  grid-column: 1/3;
}

.operator {
  background: orange;
  color: #ffffff;
}

.btn {
  border: 1px solid rgba(0, 0, 0, 0.1);
}
</style>