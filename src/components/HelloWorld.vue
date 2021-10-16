<template>
  <div class="hello">
    <h1 class="hello-text">{{ msg }}</h1>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Vue.js 시작하기'
    }
  }
}
</script>

<style scoped lang="scss">
.hello {
  &-text {
    color: green;
  }
}
</style>
