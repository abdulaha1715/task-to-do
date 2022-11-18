<template>
  <header>
    <h1>Task Tacker</h1>
  </header>
</template>

<script>
  export default {
    name: 'Header',
    props: {
      title: {
        type: String,
        default: 'Tacker'
      }
    }
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 20px;
}
</style>
