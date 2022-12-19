<template>
  <div>
    <img :src="`~~/assets/${something}.svg`" />
  </div>
</template>
<script setup>
const something = ref('something');
</script>
