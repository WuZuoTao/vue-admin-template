<template>
  <div class="app-container">
    <input v-fbind:value="n">
  </div>
</template>

<script>
export default {
  data() {
    return {
      n: '通过自定义指令-自动获取焦点    '
    }
  }
}
</script>

<style scoped>
input{
  width: 100%;
  height: 50px;
}
</style>

