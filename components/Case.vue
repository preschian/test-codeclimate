<template>
  <div>
    <input type="number" min="1" max="12" v-model="nums" />
    <p>text: {{ first(nums) }}</p>
    <p>text: {{ second(nums) }}</p>
  </div>
</template>

<script setup>
const nums = ref();

function first(number) {
  if (number === 1) {
    return 'one';
  }

  if (number === 2) {
    return 'two';
  }

  if (number === 3) {
    return 'three';
  }

  if (number === 4) {
    return 'four';
  }

  if (number === 5) {
    return 'five';
  }

  if (number === 6) {
    return 'six';
  }

  return 'invalid number';
}

function second(number) {
  if (number === 7) {
    return 'seven';
  }

  if (number === 8) {
    return 'eight';
  }

  if (number === 9) {
    return 'nine';
  }

  if (number === 10) {
    return 'ten';
  }

  if (number === 11) {
    return 'eleven';
  }

  if (number === 12) {
    return 'twelve';
  }

  return 'invalid number';
}
</script>
