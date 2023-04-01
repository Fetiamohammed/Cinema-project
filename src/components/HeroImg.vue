<template>
  <div class="heroimage">
    <img :src="heroImage" alt="cinema" />
    <div class="text"></div>
  </div>
</template>
<script>
export default {
  data() {
    return {
      heroImage: "/src/assets/img/aboutBioWH2.png",
    };
  },
};
</script>
<style scoped>
.heroimage {
  margin: auto;
}
img {
  width: 100%;
}
@media screen and (max-width: 480px) {
  .heroimage {
    margin: auto;
  }
  img {
    width: 100%;
  }
}
</style>
