<template>
  <div class="home">
    
    <HeaderNaima />
    <HeroNaima />
    <ProductsNaima />
    <GalleryNaima />
    <BrandsNaima />
    <FooterNaima />

   
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'

import HeaderNaima from '@/components/HeaderNaima.vue';
import HeroNaima from '@/components/HeroNaima.vue';
import ProductsNaima from '@/components/ProductsNaima.vue';
import GalleryNaima from '@/components/GalleryNaima.vue';
import BrandsNaima from '@/components/BrandsNaima.vue';
import FooterNaima from '@/components/FooterNaima.vue';


export default {
  name: 'Home',
  components: {
    HeaderNaima,
    HeroNaima,
    ProductsNaima,
    GalleryNaima,
    BrandsNaima,
    FooterNaima,
  }
}
</script>
