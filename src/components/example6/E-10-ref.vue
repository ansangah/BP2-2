<template>
  <div>
    <p>Count: {{ count }}</p>
    <button @click="increment">Increment</button>
  </div>
</template>

<script setup>
import { ref } from "vue";

const count = ref(0); // ref로 원시 값을 생성

const increment = () => {
  count.value += 1; // ref는 .value를 통해 값을 접근
};
</script>
