<template>
  <div>
    <SharedHeader></SharedHeader>
    <h1>test</h1>
    <Nuxt />
  </div>
</template>

<script>
import SharedHeader from '~/components/client/shared/SharedHeader.vue'

export default {
  data() {
    return {
      title: 'SuperCook - Zero Waste Recipe',
    }
  },
  head() {
    return {
      title: this.title,
    }
  },
  mounted() {},
  methods: {},
  components: { SharedHeader },
}
</script>

<style lang="scss" scoped></style>
