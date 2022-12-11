<template>
  <div id="date">
    {{date}}
  </div>
  <div id="date2">
    {{date2}}
  </div>
</template>

<script>
export default {
  name: 'declareRender',
  // Composition API
  setup() {
    const date = Date().toString()
    return {date}
  },

  // Options API
  data() {
    return {
      date2: Date().toString(),
    }
  },
}
</script>

<style scoped>

</style>
