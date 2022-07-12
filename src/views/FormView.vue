<template>
  <main id="form-view" class="form-view">
    <VueCard />
  </main>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";
import VueCard from "@/components/VueCard.vue";

@Component({
  components: {
    VueCard,
  },
})
export default class FormView extends Vue {}
</script>

<style scoped>
.form-view {
  display: flex;
  flex-direction: column;
  align-items: center;
}
</style>
