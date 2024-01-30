<script>

/* import components */
import AppHeader from './components/AppHeader.vue'
import AppMain from './components/AppMain.vue'
import AppFooter from './components/AppFooter.vue'

export default {
  name: 'App',

  /* Register components */
  components: {
    AppHeader,
    AppMain,
    AppFooter
  }
}

</script>

<template>
  <!-- user components -->
  <AppHeader></AppHeader>
  <AppMain></AppMain>
  <AppFooter></AppFooter>
</template>

<style></style>
