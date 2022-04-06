<template>
  <div class="home">
  <!-- Ini component untuk menjalankan tampilan header -->
  <TheHeader/>

 <!-- Ini component untuk menjalankan tampilan Carousle -->
  <TheCarousle/>

  <!-- Ini component untuk menjalankan tampilan Hero Produk -->
  <HeroWoman/>

   <!-- Ini component untuk menjalankan tampilan Insta Gallery -->
  <InstaGallery/>

  <!-- Ini component untuk menjalankan tampilan Patner Logo -->
  <PatnerLogo/>

  <!-- Ini component untuk menjalankan tampilan The Footer -->
  <TheFooter/>


  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
 import TheHeader from '@/components/TheHeader.vue';
 import TheCarousle from '@/components/TheCarousle.vue';
 import HeroWoman from '@/components/HeroWoman.vue';
 import InstaGallery from '@/components/InstaGallery.vue';
 import PatnerLogo from '@/components/PatnerLogo.vue';
 import TheFooter from '@/components/TheFooter.vue';



export default {
  name: 'HomeView',
  components: {
    TheHeader,
    TheCarousle,
    HeroWoman,
    InstaGallery,
    PatnerLogo,
    TheFooter,
    
  }
}
</script>
