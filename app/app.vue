<template>
  <div class="app">
    <div>
      <BannerSection />
    </div>
  </div>
</template>

<script>
import BannerSection from "./components/BannerSection.vue";
export default {
  components: {
    BannerSection,
  },
};
</script>
<style>
.app {
  background-color: #fff;
  height: 100vh;
  padding: 0;
  margin: 0;
  box-sizing: border-box;
  color: #1c1b1f;
  display: flex;
  align-items: center;
  justify-content: center;
}
</style>
