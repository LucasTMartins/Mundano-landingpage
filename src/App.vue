<template>
  <div id="app">
    <HeaderComponent />
    <HeroSection />
    <AboutSection />
  </div>
</template>

<script>
import HeaderComponent from './components/HeaderComponent.vue';
import HeroSection from './components/HeroSection.vue';
import AboutSection from './components/AboutSection.vue';

export default {
  components: {
    HeaderComponent,
    HeroSection,
    AboutSection
  }
};
</script>

<style>
@import 'bootstrap/dist/css/bootstrap.css';
</style>
