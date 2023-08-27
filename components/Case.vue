<template>
  <div>
    <input type="number" min="1" max="12" v-model="nums" />
    <p>text: {{ first(nums) }}</p>
    <p>text: {{ second(nums) }}</p>
  </div>
</template>

<script src="./case-script.js"></script>
