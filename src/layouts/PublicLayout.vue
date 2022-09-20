<template>
  <v-main class="gradiente-bg">
    <router-view />
    <PageFooter />
  </v-main>
</template>

<script>
import PageFooter from '@/components/PageFooter.vue'

export default {
  data: () => ({}),
  components: {
    PageFooter,
  },
}
</script>

<style>
.gradiente-bg {
  background: linear-gradient(
    90deg,
    rgba(2, 0, 36, 1) 0%,
    rgba(0, 255, 85, 1) 0%,
    rgba(102, 44, 223, 1) 84%
  );
}
</style>
