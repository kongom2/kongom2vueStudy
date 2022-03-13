<template>
  <table>
    <tr-component></tr-component>
  </table>
</template>

<script>
import TrComponent from "./TrComponent";
export default {
  props: {
    tableData: Array,
  },
  component: { TrComponent },
  computed: {},
};
</script>

<style></style>
