<template>
  <Hello language="vue"/>
</template>

<script>
import Hello from '../src/index.js' // 组件打包后可引入lib中的文件测试

export default {
  components: {
    Hello
  }
}
</script>
