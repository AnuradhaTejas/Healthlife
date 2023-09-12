<script setup>
import { RouterLink, RouterView } from 'vue-router'
import AppHeader from "./components/Layouts/AppHeader.vue"
import BannerPage from "./components/Layouts/BannerPage.vue"
import ChooseProgram from "./components/Layouts/ChooseProgram.vue"
import ActionPage from "./components/Layouts/ActionPage.vue"
import ClassSchedule from "./components/Layouts/ClassSchedule.vue"
import Testimonials from "./components/Layouts/Testimonials.vue"
import ContactUs from "./components/Layouts/ContactUs.vue"
import AppFooter from "./components/Layouts/AppFooter.vue"
// import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <AppHeader/> 
  <RouterView />
    <BannerPage/>
    <ChooseProgram/>
    <ActionPage/>
    <ClassSchedule/> 
    <Testimonials/>
    <ContactUs/>
    <AppFooter/>
  
    <RouterLink to="/"></RouterLink>
    <RouterLink to="/about"></RouterLink>
  
      </template>
  <!-- <header>
    <img alt="Vue logo" class="logo" src="@/assets/logo.svg" width="125" height="125" />

    <div class="wrapper">
      <HelloWorld msg="You did it!" />

      <nav> -->
       
      <!-- </nav>
    </div>
  </header> -->

  


<style scoped>

</style>
