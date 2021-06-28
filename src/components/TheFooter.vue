<template>
  <div class="footer center">
    <div>© 2021 Jonas Voland</div>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
export default defineComponent({
  name: "TheFooter",
});
</script>

<style scoped>
.footer {
  background: #111111;
  color: #7e7e7e;
  height: 51vh;
}

.center {
  display: grid;
  place-items: center;
}
</style>
