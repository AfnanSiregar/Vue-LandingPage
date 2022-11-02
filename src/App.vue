<script setup>
import AboutView from './components/AboutView.vue';
import FooterView from './components/FooterView.vue';
import FormView from './components/FormView.vue';
import HeaderView from './components/HeaderView.vue';
import HomeView from './components/HomeView.vue';
import TipsView from './components/TipsView.vue';

</script>
  
<template>
  <div class="bg-white">
    <div class="mx-auto w-11/12 z-[0]">
      <HeaderView />
      <HomeView />
      <AboutView />
      <FormView/>
      <TipsView />
      <FooterView />
    </div>
  </div>
</template>

<style scoped>

</style>
