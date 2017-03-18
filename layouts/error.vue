<template>
  <section class="container">
    error
    <h1 class="title">
      {{ error.statusCode }}
    </h1>
    <h2 class="info">
      {{ error.message }}
    </h2>
  </section>
</template>
<script>
export default {
  props: ['error']
}
</script>

<style scoped>

</style>
