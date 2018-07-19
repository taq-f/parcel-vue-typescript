<template>
  <p>
    {{ greeting }} World!!
  </p>  
</template>

<script lang="ts">
import Vue from "vue";
import Component from "vue-class-component";

@Component
export default class Hello extends Vue {
  greeting = "hello, ";
}
</script>

<style scoped>
p {
  font-size: 2em;
  text-align: center;
  color: #2e9afe;
}
</style>
