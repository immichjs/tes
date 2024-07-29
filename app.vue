<script setup lang="ts">
const data = await $fetch("https://pokeapi.co/api/v2/pokemon");
</script>

<template>
  <div>
    {{ data }}
  </div>
</template>
