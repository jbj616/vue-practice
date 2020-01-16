<template>
  <div>
    <Box color="blue" />
    <Box color="purple" />
    <Box color="green" />
    <Box color="blue" />
    <Box color="purple" />
    <Box />
  </div>
</template>

<script>
import Box from "./components/Box";

export default {
  name: "app",
  components: {
    Box
  }
};
</script>

<style scoped>
.wrap {
  display: flex;
}
</style>