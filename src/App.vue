<template>
  <router-view />
</template>

<style lang="scss">
@import "https://cdn.jsdelivr.net/npm/bulma@0.9.1/css/bulma.min.css";

#nav {
  padding: 30px;
  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
