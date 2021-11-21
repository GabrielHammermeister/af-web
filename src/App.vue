<template>
  <v-app>
    <v-system-bar
      app
      height="20"
      class="d-flex justify-center"
      >
      v-system-bar 
      </v-system-bar>
    <v-app-bar
      app
      elevation="4"
      class="d-flex justify-center"
    >
     v-app-bar
    </v-app-bar>

    <v-main>


        <v-row style="height: 100%; margin: 0">
            <v-navigation-drawer 
              permanent
              class="d-flex align-center justify-center"
            >
              <div style="height: 100%" class="d-flex align-center">v-navigation-drawer</div>
            </v-navigation-drawer>
            <v-content style="padding: 0">
              <div 
                style="height: 100%"
                class="d-flex align-center justify-center"
              >v-content</div>
            </v-content>
        
        </v-row>


    </v-main>

    <v-footer
      class="d-flex justify-center"
    >v-footer</v-footer>
    <v-bottom-navigation
      class="d-flex align-center"
    >v-bottom-navigation</v-bottom-navigation>
  </v-app>
</template>

<script>

export default {
  name: 'App',
  data: () => ({
    //
  }),
};
</script>
