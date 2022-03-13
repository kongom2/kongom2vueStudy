<template>
  <table-component :table-data="tableData" />
</template>

<script>
import TableComponent from "./TableComponent";
export default {
  components: { TableComponent },
  data() {
    return {
      tableData: [
        ["", "", ""],
        ["", "", ""],
        ["", "", ""],
      ],
    };
  },
  computed: {},
  methods: {},
  watch: {},
};
</script>
<style scoped></style>
