<template>
  <div class="home-page">
    <HomeLanding />
    <HomeVideoBackground />
    <footer>
      VA DRONES ・ 2022
    </footer>
  </div>
</template>

<style lang="postcss" scoped>
.home-page {
  position: relative;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: flex-end;
  padding-bottom: var(--space-xl);
  height: 100%;

  footer {
    position: absolute;
    bottom: 10px;
    left: 0;
    z-index: 100;
    color: var(--gray-400);
    font-size: var(--step--2);
    width: 100%;
    text-align: center;
  }
}
</style>

<route lang="yaml">
meta:
  layout: home
</route>
