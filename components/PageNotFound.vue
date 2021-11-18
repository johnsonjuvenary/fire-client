<template>
  <div>
    <h3>Page Not Found</h3>
    <img :src="require('@/assets/images/fe25.jpg')" alt="" />
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
div {
  display: flex;
  align-items: center;
  justify-content: center;
  width: 50rem;
}
h3 {
  font-size: 3rem;
}
img {
  width: 15rem;
  margin: 0 auto;
}
</style>
