<template>
  <v-app>
    <v-app-bar
      app
      color="primary"
      dark
    >

      <div class="d-flex align-left">
        <h1>POPCORN board</h1>
      </div>
        
    </v-app-bar>

    <v-main>
      <v-container fluid="true">
        <v-row>
          <v-col cols="1">
            <div>
              <v-img src="assets/popcorn/problems.png" contain="true" height="200" />
            </div>
          </v-col>
          <v-col cols="2">
            <div>
              <v-img src="assets/popcorn/options.png" contain="true" height="200" />
            </div>
          </v-col>
          <v-col cols="2">
            <div>
              <v-img src="assets/popcorn/possible-experiments.png" contain="true" height="200" />
            </div>
          </v-col>
          <v-col cols="2">
            <div>
              <v-img src="assets/popcorn/commited.png" contain="true" height="200" />
            </div>
          </v-col>
          <v-col cols="2">
            <div>
              <v-img src="assets/popcorn/ongoing.png" contain="true" height="200" />
            </div>
          </v-col>
          <v-col cols="2">
            <div>
              <v-img src="assets/popcorn/review.png" contain="true" height="200" />
            </div>
          </v-col>
          <v-col cols="1">
            <div>
              <v-img src="assets/popcorn/next.png" contain="true" height="200" />
            </div>
          </v-col>
        </v-row>
        <v-row>
          <v-col cols="12">
            <HelloWorld/>
          </v-col>
        </v-row>
      </v-container>
    </v-main>
  </v-app>
</template>

<script>
import HelloWorld from './components/HelloWorld';

export default {
  name: 'App',

  components: {
    HelloWorld,
  },

  data: () => ({
    //
  }),
};
</script>
