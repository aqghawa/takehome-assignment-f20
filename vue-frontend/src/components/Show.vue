<template>
  <!-- PART 4: Add your code here -->
  <div>
    <p>{{ name }}</p>
    <Counter v-bind:initCount="episodes_seen"/>
  </div>
</template>

<script>
// PART 4: Add your code here
import Counter from "./Counter.vue";
export default {
  components: {
    Counter
  },
  props: ["id","name","episodes_seen"]
};
</script>

<style>
</style>
