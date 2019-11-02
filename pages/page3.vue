<template>
  <b-container>
    <Page :title="text.title" :body="text.body" :footer="text.footer"/>
  </b-container>
</template>

<script>
import { Page } from '../components/'

export default {
  components: {
    Page
  },
  computed: {
    text () {
      return this.$t('page_3')
    }
  }
}
</script>
