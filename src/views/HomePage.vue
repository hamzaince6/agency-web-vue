<script setup>
import AppHeader from '../components/global/AppHeader.vue'
import HomePageHero from '../components/HomePageHero.vue'
import HomePageAbout from "@/components/HomePageAbout.vue";
import HomePageServices from "@/components/HomePageServices.vue";
import HomePageWorks from "@/components/global/HomePageWorks.vue";
</script>

<template>
  <AppHeader />
  <HomePageHero/>
  <HomePageAbout/>
  <HomePageServices/>
  <home-page-works/>
</template>




