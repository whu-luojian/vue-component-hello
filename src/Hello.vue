<template>
  <div class="title">
    {{language}}, Hello World!
  </div>
</template>

<script>
export default {
  props: {
    language: {
      type: String,
      required: true
    }
  }
}
</script>

<style lang='less' scoped>
.title {
  text-align: center;
  font-size: 20px;
  font-weight: bold;
}
</style>
