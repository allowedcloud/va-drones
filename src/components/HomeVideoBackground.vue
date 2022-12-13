<template>
  <div class="video-wrapper">
    <video muted autoplay playsinline loop poster="/images/home-video-poster.png">
      <source src="/videos/home-video-background.mp4" type="video/mp4">
    </video>
  </div>
</template>

<style lang="postcss" scoped>
.video-wrapper {
  width: 100%;
  height: 100%;
  position: absolute;
  top: 0;
  left: 0;
  z-index: 0;
}
video {
  object-fit: cover;
  width: 100%;
  height: 100%;
}
</style>
