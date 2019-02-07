<template lang="html">
  <input type="text" name="calendar" id="calendar">
</template>

<script>
export default {
  mounted() {
    $('#calendar').datepicker();
  }
}
</script>

<style lang="css" scoped>
</style>
