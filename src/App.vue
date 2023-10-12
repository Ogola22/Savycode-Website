<script>
import { RouterLink, RouterView } from 'vue-router'
import FooteterComponent from './components/HomeMaster/FooteterComponent.vue';
import NavbarComponent from './components/HomeMaster/NavbarComponent.vue';

export default {
  components: { NavbarComponent, FooteterComponent }
}

</script>

<template>

  <navbar-component></navbar-component> 
  <RouterView />
  <footeter-component></footeter-component>

</template>

<style></style>
