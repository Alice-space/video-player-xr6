<template>
  <a class="float">
    CONTROL PANEL
  </a>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  name: "ControlPanel",
});
</script>

<style scoped>
.float {
  position: fixed;
  opacity: 70%;
  width: 300px;
  height: 300px;
  top: 20px;
  left: 20px;
  background-color: #0c9;
  color: #fff;
  text-align: center;
  box-shadow: 2px 2px 3px #999;
}
</style>
