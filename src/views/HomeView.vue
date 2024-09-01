<template>
  <div class="home">
    <img alt="Coffee logo" src="../assets/coffee_logo.png">
    <GeneralInfo msg="Välkommen till Restaurant Kaffepaus"/>
  </div>
</template>

<script>
// @ is an alias to /src
import GeneralInfo from '@/components/GeneralInfo.vue';

export default {
  name: 'HomeView',
  components: {
    GeneralInfo
  }
}
</script>
