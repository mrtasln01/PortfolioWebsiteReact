<template>
  <h1 class="logo-heading">
    <router-link to="/" tag="a">MURAT ASLAN</router-link>
  </h1>
</template>

<script>
export default {
  name: "HeaderLogo"
};
</script>

<style scoped lang="scss">
.logo-heading {
  color: var(--h-logo);
  font-size: 34px;
  letter-spacing: 3px;
  @media (max-width: 720px) {
    font-size: 24px;
  }
}
</style>
