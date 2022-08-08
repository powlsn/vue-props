<script setup>
import TheChild from './TheChild.vue';
import SlotChild from './SlotChild.vue'
import ScopedSlotChild from './ScopedSlotChild.vue'
</script>

<template>
  <h1>Workshop</h1>
  <!-- ### props ### -->
  <!-- <the-child value="hello"></the-child> -->
  
  <!-- ### slot / named slots ### -->
  <!-- <slot-child>
    <template v-slot:default>
      <h2>hello</h2>
    </template>

    <template v-slot:header>
      <h3>the header</h3>
    </template>
  </slot-child> -->

  <!-- ### scoped slot ### -->
  <!-- <scoped-slot-child>
    <template v-slot="slotProps">
    <ul>
      <li v-for="item in slotProps.list">
        {{ item.firstname }}
      </li>
    </ul>
    </template>
  </scoped-slot-child> -->
</template>
