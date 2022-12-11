<script setup>
import HelloWorld from './components/HelloWorld.vue'
import DeclareRender from '/@components/DeclareRender.vue'
import ResponsiveVariable from '/@components/ResponsiveVariable.vue'
import EventListener from '/@components/EventListener.vue'
import ConditionIf from '/@components/ConditionIf.vue'
import ForDirectiveExample from '/@components/ForDirectiveExample.vue'
import ComputedProps from '/@components/ComputedProps.vue'
import WatchAndWatchEffect from '/@components/WatchAndWatchEffect.vue'
</script>

<template>
  <div>
    <a href="https://vitejs.dev" target="_blank">
      <img src="/vite.svg" class="logo" alt="Vite logo" />
    </a>
    <a href="https://vuejs.org/" target="_blank">
      <img src="./assets/vue.svg" class="logo vue" alt="Vue logo" />
    </a>
  </div>
<!--  <HelloWorld msg="Vite + Vue" />-->
<!--  <Declare-render/>-->
<!--  <ResponsiveVariable/>-->
<!--  <EventListener/>-->
<!--  <ConditionIf/>-->
<!--  <ForDirectiveExample/>-->
<!--  <ComputedProps/>-->
  <WatchAndWatchEffect/>
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
