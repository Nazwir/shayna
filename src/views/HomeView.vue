<template>
  <div class="home">

    <HeaderShaynaView/>
    <HeroShayna/>
    <WomanShayna/>
    <InstaShayna/>
    <PartnerShayna/>
    <FooterShayna/>

  </div>  
</template>

<script>
// @ is an alias to /src
//import HelloWorld from '@/components/HelloWorld.vue'
import HeaderShaynaView from '@/components/HeaderShaynaView.vue'
import HeroShayna from '@/components/HeroShayna.vue';
import WomanShayna from '@/components/WomanShayna.vue';
import InstaShayna from '@/components/InstaShayna.vue';
import PartnerShayna from '@/components/PartnerShayna.vue';
import FooterShayna from '@/components/FooterShayna.vue';
//import carousel from 'vue-owl-carousel'

export default {
  name: "HomeView",
  components: {
    HeaderShaynaView, HeroShayna, WomanShayna, InstaShayna, PartnerShayna, FooterShayna
  }
}
</script>
