<template>
  <header>
    <h1>Task Tacker</h1>
    <Button text="Add Task" color="green" />
  </header>
</template>

<script>
  import Button from './Button'

  export default {
    name: 'Header',
    props: {
      title: {
        type: String,
        default: 'Tacker'
      }
    },
    components: {
      Button,
    },
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
