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