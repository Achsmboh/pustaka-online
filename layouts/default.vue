<template>
  <div id="app">
    <HeaderWeb />
    <Nuxt />
    <FooterWeb />
  </div>
</template>

<script>
// Memanggil component sesuai lokasi masing-masing
import HeaderWeb from '@/components/HeaderWeb.vue'
import FooterWeb from '@/components/FooterWeb.vue'
export default {
  // Dideklarasikan agar dapat diakses oleh template
  components: {
    HeaderWeb,
    FooterWeb,
  },
}
</script>
