<template>
  <div>
    <p>I'm a Counter!</p>
    <p>Current count is {{ count }}</p>
    <button v-on:click="count++">Increase</button>
    <button v-on:click="count--">Decrease</button>
  </div>
</template>

<script>
export default {
  props: ["initCount"],
  data() {
    return {
      count: this.initCount
    };
  }
};
</script>

<style>
</style>

