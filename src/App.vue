<script setup>
import Header from './components/Header/Header.vue';
import HeadingHero from './components/hero/HeadingHero.vue'
import FeaturesSection from './components/section/FeaturesSection.vue'
import LatestProductsSection from './components/section/LatestProductsSection.vue' 
import PopularProductsSection from './components/section/PopularProductsSection.vue'
import NewsletterSection from './components/section/NewsletterSection.vue'
import Footer from './components/footer/Footer.vue'
</script>

<template>
  <section class="relative">
    <Header />
    <HeadingHero />
    <FeaturesSection />
    <LatestProductsSection />
    <PopularProductsSection />
    <NewsletterSection />
    <Footer />
  </section>
</template>
