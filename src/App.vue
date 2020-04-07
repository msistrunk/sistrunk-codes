<template>
  <v-app id="inspire" class="display-4">
    <v-row justify="center" align="center">
      <h1>COMING SOON</h1>
    </v-row>
    <v-row justify="center" align="start">
        <v-progress-circular
          :indeterminate="true"
          :size="60"
          color="light-blue"
        ></v-progress-circular>
    </v-row>
  </v-app>
</template>

<script>

export default {
  name: 'App',

  data: () => ({
    //
  }),

  created () {
    this.$vuetify.theme.dark = true
  },
};
</script>

<style scoped>
h1 {
  font-size:3.5em;
  font-weight:100;
  letter-spacing:.5em;
  text-shadow:0px 0px 20px #6EC3EC;
  color:#6EC3EC;
  display:inline-block;
}
</style>
