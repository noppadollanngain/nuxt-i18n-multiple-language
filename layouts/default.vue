<template>
  <div>
    <Header />
    <nuxt />
    <Footer />
  </div>
</template>

<script>
import { Header, Footer } from '../components/Layouts/'

export default {
  components: {
    Header,
    Footer
  }
}
</script>
