<template>
  <div class="d-flex flex-column h-100">
    <Header />
    <router-view />
    <Footer />
  </div>
</template>

<script>
import Header from '@/components/Header'
import Footer from '@/components/Footer'
export default {
  components: {
    Header,
    Footer
  }
}
</script>
<style lang="scss">
@import './assets/style/index';
</style>
