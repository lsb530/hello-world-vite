<template>
  <div style="width: 200px">
    <ol>
      <li v-for="item in arrItems">{{ item }}</li>
    </ol>
    <ol>
      <li v-for="item in objItems">{{ item }}</li>
    </ol>
  </div>
</template>

<script>
import {reactive} from 'vue'

export default {
  name: 'ForDirectiveExample',
  // Composition API
  setup() {
    const arrItems = reactive(['1번 아이템', '2번 아이템', '3번 아이템'])
    const objItems = reactive({1: '1번 아이템', 2: '2번 아이템', 3: '3번 아이템'})
    return {arrItems, objItems}
  }
}
</script>

<style scoped>

</style>
