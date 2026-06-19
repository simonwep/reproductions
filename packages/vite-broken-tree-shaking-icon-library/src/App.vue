<template>
  Hello world!

  <!-- Uncomment for repro -->
  <!-- <Icons/> -->
</template>

<script setup lang="ts">
// Uncomment for repro
// This way the library used in Icons.vue is properly tree-shaked
// import Icons from './Icons.vue';

// Comment out for repro
// This way the whole library is bundled and NOT tree-shaked
void import('./Icons.vue');
</script>
