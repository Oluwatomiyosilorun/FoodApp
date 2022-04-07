<template>
  <div>
    <div class="content">
      <AppMenu />
      <Nuxt />
      <AppFooter/>
    </div>
  </div>
</template>

<script>
import AppMenu from '@/components/AppMenu.vue'
import AppFooter from '@/components/AppFooter.vue'

export default {
  components: {
    AppMenu,
    AppFooter
  }
}
</script>

<style scoped>
html {
  font-family: "Mulish";
  font-weight: 16px;
  font-weight: 300;
}

h1,
h2,
h3,
h4 {
  font-family: "Poppins";
  font-weight: 16px;
  font-weight: 600;
}
</style>
