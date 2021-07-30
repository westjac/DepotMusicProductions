<template>
  <v-row justify="center">
    <v-col cols="12" sm="8" md="6">
      <div class="spacer"></div>
      <logo />
      <div class="text-center">
        <v-btn
          to="/corporate"
          class="ma-2"
          outlined
          x-large
          color="white">
          Corporate
        </v-btn>
        <v-btn
          to="/production"
          class="ma-2"
          outlined
          x-large
          color="white">
          Production
        </v-btn>
        <v-btn
          to="/install"
          class="ma-2"
          outlined
          x-large
          color="white">
          Instalations
        </v-btn>
        <v-btn
          to="/sales"
          class="ma-2"
          outlined
          x-large
          color="white">
          Sales
        </v-btn>
      </div>
    </v-col>
  </v-row>
</template>

<script>
import Logo from '~/components/logo.vue'

export default {
  components: {
    Logo
  }
}
</script>

<style scoped>
.spacer {
  height: 25%;
}
</style>
