<template>
  <v-app>
    <LandingPage />
    <!-- </v-main> -->
  </v-app>
</template>

<script>
import LandingPage from "./components/LandingPage";

export default {
  name: "App",

  components: {
    LandingPage,
  },

  data: () => ({
    //
  }),
};
</script>

<style>
* {
  align-self: center;
}
</style>