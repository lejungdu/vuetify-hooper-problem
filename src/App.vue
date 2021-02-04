<template>
  <v-app>
    <v-app-bar
      app
      color="primary"
      dark
    >
    </v-app-bar>

    <v-main>
      <SlideShow/>
    </v-main>
  </v-app>
</template>

<script>
import SlideShow from './components/SlideShow';

export default {
  components: { 
    SlideShow
  },
};
</script>
