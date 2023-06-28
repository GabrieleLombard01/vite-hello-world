<script>
import appTitle from './components/appTitle.vue';
import appHero from './components/appHero.vue';
export default {
  data() {
    return {

    }
  },
  components: {
    appTitle: appTitle,
    appHero: appHero,
  }
}
</script>

<template>
  <!--TITLE:-->
  <appTitle />

  <!--JUMBO:-->
  <appHero />
</template>

<style></style>
