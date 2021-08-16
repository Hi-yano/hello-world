<template>
  <!-- HTMLを記述する部分 -->
  <div class="helloWorld">
    {{ msg2 }}
  </div>
</template>

<script>
  // JSを記述する部分
  export default {
  name: 'HelloWorld',
  props: {
    msg: String,
    msg2: String
  }
}
</script>

<style scoped>
  /* CSSを記述する部分 */
</style>