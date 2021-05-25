<template>

  <main class="container">
    <app-header/>
    <app-restaurant-info :datasource="fooddata"/>
  </main>
</template>

<script>
import AppMenu from '../components/AppMenu.vue'
import AppRestaurantInfo from '../components/AppRestaurantInfo.vue'
import { mapState } from 'vuex';

export default {
  components: { 
    AppMenu, 
    AppRestaurantInfo 
  },
  computed: {
    ...mapState([
      'fooddata',
    ])
  },  

}
</script>

<style>

</style>
