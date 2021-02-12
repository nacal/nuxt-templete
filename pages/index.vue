<template>
  <div class="container">
    <div>
      <Logo />
      <h1 class="title">nuxt-templete</h1>
      <div class="links">
        <a
          href="https://nuxtjs.org/"
          target="_blank"
          rel="noopener noreferrer"
          class="links__item"
        >
          Nuxt.js Documentation
        </a>
        <a
          href="https://github.com/nkthkr/nuxt-templete"
          target="_blank"
          rel="noopener noreferrer"
          class="links__item"
        >
          This Templete GitHub
        </a>
        <router-link to="test"> test </router-link>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style lang="scss" scoped>
.container {
  display: flex;
  align-items: center;
  justify-content: center;
  min-height: 75vh;
  margin: 0 auto;
  text-align: center;
}

.title {
  display: block;
  font-size: 100px;
  font-weight: 300;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  padding-bottom: 15px;
  font-weight: 300;
  color: #fff;
}

.links {
  padding-top: 15px;
  text-decoration: underline;

  &__item + &__item {
    margin-top: 15px;
  }
}
</style>
