<template>
  <div class="text-wrapper">
    <h1>
      VA Drones
    </h1>
    <ul>
      <li>
        <RouterLink to="/about">
          About
        </RouterLink>
      </li>

      <li>
        <RouterLink to="/services">
          Services
        </RouterLink>
      </li>

      <li>
        <RouterLink to="/portfolio">
          Portfolio
        </RouterLink>
      </li>
    </ul>
    <p>
      Want your business to stand out?
      <br>
      Need breathtaking footage?
      <br>
      Let us help.
    </p>
  </div>
</template>

<style lang="postcss" scoped>
.text-wrapper {
  width: 80%;
  position: absolute;
  bottom: 20%;
  left: 10%;
  z-index: 100;
  color: white;
  h1 {
    font-size: var(--step-3);
    font-weight: 400;
    font-family: serif;
  }
  p {
    font-weight: 600;
    letter-spacing: 0.8px;
  }
  ul {
    display: inline-flex;
    flex-direction: row;
    gap: 20px;
    margin: var(--space-2xs) 0;
    margin-top: 0;
    li {
      border-radius: 6px;
      padding: var(--space-3xs) var(--space-2xs);
      text-transform: uppercase;
      border: 1px solid var(--orange);
      color: var(--orange);
      backdrop-filter: blur(2px) brightness(0.8);
    }
  }
}
</style>
