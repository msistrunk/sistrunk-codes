<template>
  <v-app id="inspire" class="display-4">
    <div class="container">
      <h1>COMING SOON</h1>
      <div class="text-center ma-12">
        <v-progress-circular
          :indeterminate="true"
          :size="60"
          color="light-blue"
        ></v-progress-circular>
      </div>
    </div>
  </v-app>
</template>

<script>
// import HelloWorld from './components/HelloWorld';

export default {
  name: 'App',

  // components: {
  //   HelloWorld,
  // },

  data: () => ({
    //
  }),

  created () {
    this.$vuetify.theme.dark = true
  },
};
</script>

<style scoped>
.container {
  font-size:16px;
  top:20%;
  position:absolute;  
  color:#FFFFFF;
  text-align:center;
}

h1 {
  font-size:3.5em;
  font-weight:100;
  letter-spacing:.5em;
  text-shadow:0px 0px 20px #6EC3EC;
  color:#6EC3EC;
  display:inline-block;
}
</style>
