<template>
  <h2>我爱你赵丽颖</h2>
  <button @click="count++">爱了{{count}}次</button>
</template>

<script>
export default {
  name: "MyButton",
  data() {
    return {
      count:0,
    }
  }
}
</script>

<style scoped>
  h2 {
    color: aquamarine;
  }
</style>