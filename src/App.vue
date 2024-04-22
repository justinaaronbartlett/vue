<script setup>
import { reactive, onMounted } from 'vue';

const weatherData = reactive({
  fahrenheit: null, 
});

onMounted(async () => {
 
});
</script>

<template>
  <div>
    <p>Current Temperature: °F</p>
  </div>
</template>


<style scoped>

</style>
