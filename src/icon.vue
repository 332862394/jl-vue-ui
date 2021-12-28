<template>
  <svg class="g-icon">
    <use :xlink:href="`#i-${iconName}`" />
  </svg>
</template>

<script>
export default {
  props: ["iconName"],
};
</script>

<style lang="scss" scoped>
.g-icon {
  width: 1em;
  height: 1em;
}
</style>