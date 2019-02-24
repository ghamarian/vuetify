<template>
  <v-app>
    <v-toolbar app>
      <v-toolbar-title class="headline text-uppercase">
        <span>Vuetify</span>
        <span class="font-weight-light">MATERIAL DESIGN</span>
      </v-toolbar-title>
      <v-spacer></v-spacer>
      <v-btn flat href="https://github.com/vuetifyjs/vuetify/releases/latest" target="_blank">
        <span class="mr-2">Latest Release</span>
      </v-btn>
    </v-toolbar>

    <v-content>
      <v-container fluid grid-list-md fill-height>
        <v-layout row wrap justify-space-around>
          <v-flex d-flex md12>
            <HelloWorld msg="hello"/>
          </v-flex>
          <!-- <v-flex d-flex md8>
            <HelloWorld msg="hello"/>
          </v-flex>
          <v-flex d-flex md2>
            <HelloWorld msg="hello"/>
          </v-flex> -->
        </v-layout>
      </v-container>
    </v-content>
  </v-app>
</template>

<script>
import HelloWorld from "./components/HelloWorld";

export default {
  name: "App",
  components: {
    HelloWorld
  },
  data() {
    return {
      //
    };
  }
};
</script>
