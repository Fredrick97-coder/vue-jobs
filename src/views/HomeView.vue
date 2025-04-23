<script setup>
import Hero from "@/components/Hero.vue";
import HomeCards from "@/components/HomeCards.vue";
import JobListings from "@/components/JobListings.vue";
</script>

<template>
  <Hero title="Vue developer" subTitle="I love Vue JS" />
  <HomeCards />
  <JobListings :limit="3" :show-btn="true" />
</template>
