<template>
  <v-app-bar app color="#111111" dark flat class="px-8">
    <v-btn icon>
        <v-icon color="#A7121D">fas fa-dragon</v-icon>
    </v-btn>
    <v-spacer></v-spacer>
    <v-btn text @click="scroll('home')">Home</v-btn>
    <v-btn text @click="scroll('Project')">Project</v-btn>
    <v-btn text @click="scroll('About')">About</v-btn>
    <v-btn text @click="scroll('Contact')">Contact</v-btn>
    <v-btn text @click="scroll('Information')">Information</v-btn>
  </v-app-bar>
</template>

<script>
export default {
        scroll(refName){
            const element = document.getElementById(refName);
            element.scrollInroView({behaviour: "smooth"});
        }
}
</script>

<style>
</style>
