<template>
  <div class="layout">
    <header><TheHeader /></header>
    <main>
      <slot></slot>
    </main>
    <footer><TheFooter /></footer>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import TheFooter from '../components/TheFooter.vue'
import TheHeader from '../components/TheHeader.vue'
export default defineComponent({
  name: "LayoutFull",
  components: {
    TheFooter,
    TheHeader
  }
});
</script>

<style scoped>
.layout {
  display: grid;
  grid-auto-rows: auto 1fr auto;
}
</style>