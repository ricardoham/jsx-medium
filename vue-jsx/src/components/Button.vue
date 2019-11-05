<template>
  <button
    id="example"
    v-on:click="handleClick"
  >
    Click here!
  </button>
</template>

<script>
export default {
  name: 'Button',
  methods: {
    handleClick: function() {
      alert('The buttons was clicked')
    }
  }

}
</script>

<style>

</style>
