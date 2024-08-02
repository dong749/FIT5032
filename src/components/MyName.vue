<template>
  <div>
    Welcome: {{ name }}
    <br />
    Xudong Ren's GitHub https://github.com/dong749
  </div>
</template>

<script setup>
const name = 'Xudong Ren'
</script>

<style scoped>
div {
  font-size: 20px;
  color: #42b983;
}

a {
  color: #007bff;
  text-decoration: none;
}

a:hover {
  text-decoration: underline;
}
</style>
