<script setup>
import Navigation from "@/components/Navigation.vue";
import HomeView from "./components/HomeView.vue";
import sponser from "@/components/sponser.vue";
import TimeLine from "./components/TimeLine.vue";
import Alumini from "./components/Alumini.vue";
import footerss from "./components/footerss.vue";
import { RouterLink, RouterView } from 'vue-router'
import GalleryVue from "./components/Gallery.vue";

</script>

<template>
  <Navigation />
  <HomeView/>
  
  <TimeLine/>
  <GalleryVue/>
  <sponser/>
  <alumini/>
  <footerss/>
</template>
<style >


</style>
