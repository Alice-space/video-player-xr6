<template>
  <XRDemo/>
  <ControlPanel/>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import XRDemo from './components/XRDemo.vue'
import ControlPanel from './components/ControlPanel.vue'
require('aframe')

export default defineComponent({
  name: 'App',
  components: {
    XRDemo,
    ControlPanel
  }
});
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
