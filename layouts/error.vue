<template>
  <div class="error">
  </div>
</template>
<script>
  export default {
    mounted: function () {
      console.log('Error page has been mounted' + this.$route.path)
    }
  }
</script>
<style>
  .error {
    height: 100vh;
    background-color:red;
  }
</style>