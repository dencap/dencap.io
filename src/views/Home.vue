<template>
  <section class="hero is-fullheight">
    <div class="hero-body">
      <div class="container has-text-centered">
        <img src="https://cdn.emk.dev/dencap/favicon.png" width="50px" />
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "Home"
};
</script>
<style lang="scss" scoped>
.hero {
  background: rgb(247, 249, 252);
  background: radial-gradient(
    circle,
    rgba(247, 249, 252, 1) 0%,
    #c5cee0 100%
  ) !important;
  img {
    width: 50px;
  }
}
</style>
