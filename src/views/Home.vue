<template>
  <div class="home">
    <video-player></video-player>
  </div>
</template>

<script>
import VideoPlayer from "@/components/VideoPlayer/index.vue";
export default {
  name: "Home",
  components: {
    VideoPlayer,
  },
};
</script>

<style lang="scss" scoped>
.home {
  position: relative;
  width: 100%;
  height: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: #666;
}
</style>

