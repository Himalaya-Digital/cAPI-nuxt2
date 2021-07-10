<template>
  <div>
    <Header />
    <Nuxt />
    <Footer />
  </div>
</template>

<script lang="ts">
import { defineComponent } from '@vue/composition-api'

export default defineComponent({
  components: {
    Header: () => import('./header.vue'),
    Footer: () => import('./footer.vue'),
  },
  setup() {},
})
</script>
