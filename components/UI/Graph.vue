<template>
  <div class="graph">
    <div class="graph-bar" :style="style"></div>
  </div>
</template>

<script>
export default {
  props: {
    value: Number,
    maxValue: Number,
  },
  computed: {
    style() {
      return `width: ${(this.value / this.maxValue) * 100}%`;
    },
  },
};
</script>

<style scoped>
.graph {
  width: 260px;
  height: 40px;
  background-color: #f4f4f4;
  position: relative;
}

.graph-bar {
  position: absolute;
  top: 0;
  left: 0;
  height: 100%;
  background: #613a93;
}
</style>
