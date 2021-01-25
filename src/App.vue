<template>
  <div id="app">
    <BestProductTitle title="Best Product" />
    <p>This is the best product you can't live without</p>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";
import BestProductTitle from "./components/BestProductTitle.vue";

@Component({
  components: {
    BestProductTitle
  }
})
export default class App extends Vue {}
</script>

<style>
#app {
  color: #2c3e50;
  font-size: 16px;
  text-align: center;
  margin-top: 60px;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
