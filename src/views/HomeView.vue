<template>
  <v-app :style="{background: $vuetify.theme.themes.dark.background}"></v-app>
  <NavBar />
  <v-container fluid>
    <v-row>
      <v-col cols="6">
        <v-img src="DSC_9800.jpg" contain max-height="300">
        </v-img>
      </v-col>
      <v-col cols="6">
        <h5 class="red--text text-darken-4 top">Hello I'm Isaac</h5>
      </v-col>
    </v-row>
  </v-container>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

// Components
import NavBar from '../components/NavBar.vue';

export default defineComponent({
  name: 'HomeView',

  components: {
    NavBar,
  },
});
</script>
