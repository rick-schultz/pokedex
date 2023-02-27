<script>
import aosMixin from '~/mixins/aos'
export default {
  mixins: [aosMixin],
  data: () => ({
    drawer: null
  }),
}
</script>

<template>
  <div class="wrapper">
    <Header />
    <main>
      <NuxtPage />
    </main>
    <Footer />
  </div>
</template>

<style src="~/assets/scss/global.scss" lang="scss" />

<style lang="scss" scoped>
.wrapper {
  display: flex;
  flex-direction: column;
  main {
    margin: auto;
    max-width: 1200px;
    min-height: calc(100vh - 9rem);
    padding-bottom: 1rem;
    padding-top: 1rem;
  }
}
</style>