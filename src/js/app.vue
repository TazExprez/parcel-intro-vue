<template>
  <h2>This is a {{ framework }} application!</h2>
</template>

<script>
export default {
  data() {
    return { framework: "VueJS" };
  }
};
</script>

<style lang="scss" scoped>
h2 {
  color: green;
}
</style>
