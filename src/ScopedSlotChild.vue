<script setup>
const ppl = [
  { firstname: 'john', lastname: 'wick'},
  { firstname: 'jane', lastname: 'smith'},
  { firstname: 'jim', lastname: 'doe'},
]
</script>

<template>
  <slot :list="ppl"></slot>
</template>
