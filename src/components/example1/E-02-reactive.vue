<template>
  <div>{{ fullName }}</div>
</template>

<script setup>
import { computed, onMounted, ref } from "vue";

const firstName = ref("Kyungsu");
const lastName = ref("Lee");

const fullName = computed(() => `${firstName.value} ${lastName.value}`);

onMounted(() => {
  setTimeout(() => {
    firstName.value = "KSL";
  }, 2000);
});
</script>
