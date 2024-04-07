<template>
  <footer class="d-flex align-items-center justify-content-center mt-5">
    Copyright &copy; {{ new Date().getFullYear()}}
  </footer>
</template>

<script>
// eslint-disable-next-line
export default {
  name: 'App'
}
</script>

<style>
footer{
  background: cyan;
  color: black;
  min-height: 3em;
  font-size: 0.8em;
}
</style>
