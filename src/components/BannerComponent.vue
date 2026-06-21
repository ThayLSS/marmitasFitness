<template>
  <div id="main-banner" style="background-image: url('/img/banner.png');">
    <h1>Marmitas Fitness</h1>
  </div>
</template>

<script>
export default {
  name: "BannerComponent"
}
</script>

<style scoped>
#main-banner {
  background-position: center;
  background-size: cover;
  height: 400px;
  display: flex;
  align-items: center;
  justify-content: flex-start;
  width: 100%;
}

#main-banner h1 {
  color: #fff;
  text-align: center;
  font-size: 60px;
  background-color: rgba(34, 47, 62, 0.7);
  padding: 20px 40px;
  border-top-right-radius: 30px;
  border-bottom-right-radius: 30px;
}
</style>