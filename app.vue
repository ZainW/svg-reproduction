<template>
  <div>
    <img :src="`~/assets/${someref}.svg`" />
  </div>
</template>
<script setup>
const somref = ref('something');
</script>
