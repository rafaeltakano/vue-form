<template>
  <main id="form-view">
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
