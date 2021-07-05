<template>
  <div class="hero">
    <h3>{{ msg }}</h3>
  </div>

</template>

<script>
export default {
  name: 'Hero',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->

<style scoped>
h3 {
  color: red;
}

</style>
