<template>

  <main class="container">
    <app-header/>
    <app-restaurant-info/>
  </main>
</template>

<script>
import AppMenu from '../components/AppMenu.vue'
import AppRestaurantInfo from '../components/AppRestaurantInfo.vue'
export default {
  components: { AppMenu, AppRestaurantInfo },}
</script>

<style>

</style>
