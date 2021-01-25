<template>
  <div class="title">
    <h1>{{ title }}</h1>
  </div>
</template>

<script lang="ts">
import { Component, Prop, Vue } from "vue-property-decorator";

@Component
export default class BestProductTitle extends Vue {
  @Prop() private title!: string;
}
</script>

<style scoped></style>
