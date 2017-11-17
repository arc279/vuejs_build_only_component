<template>
  <div class="message">
    {{ message }}
  </div>
</template>

<style scoped>
  .message {
    color: blue;
  }
</style>

<script>
module.exports = {
  data () {
    return {
      message: 'hello world'
    };
  }
};
</script>
