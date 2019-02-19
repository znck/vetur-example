<script>
export default {
  props: {
    name: String,
    size: String,
  }
}
</script>

<template>
  <div :class="size">{{ name }}</div>
</template>

<style>
.small {
  font-size: 10px;
}
.medium {
  font-size: 14px;
}
.large {
  font-size: 18px;
}
</style>