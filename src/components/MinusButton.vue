<template>
  <button class="calculator-button" v-on:click="$emit('dec-val')">
    <span>-</span>
  </button>
</template>

<script>
export default {
  name: "MinusButton"
};
</script>

<style scoped>
.calculator-button {
  border: none;
  line-height: 1;
  overflow: hidden;
  display: inline-block;
  width: 44px;
  height: 44px;
  content: "";
  font-size: 30px;
  color: white;
  background: #61d5a7;
  border-radius: 50%;
  cursor: pointer;
  box-sizing: border-box;
  font-weight: lighter;
  padding-bottom: 4px;
}
</style>