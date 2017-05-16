<template>
  <div class="loader">
  </div>
</template>

<script>
export default {
  ready () {
      this.$route.router.go({path: '/seller', replace: true})
  }
}
</script>

<style scoped>

.loader {
  width: 100%;
  height: 100%;
  z-index: 1100;
  position: absolute;
  background-color: white;
}
.loader img{
  width: 100%;
}
</style>
