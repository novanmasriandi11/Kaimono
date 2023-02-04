<template>
  <div class="home">
    <HeaderStore />
    <HeroStore />
    <WomenProduct />
    <InstaProduct />
    <PartnerStore />
    <FooterStore />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from "@/components/HelloWorld.vue";
import HeaderStore from "@/components/HeaderStore.vue";
import HeroStore from "@/components/HeroStore.vue";
import WomenProduct from "@/components/WomenProduct.vue";
import InstaProduct from "@/components/InstaProduct.vue";
import PartnerStore from "@/components/PartnerStore.vue";
import FooterStore from "@/components/FooterStore.vue";

export default {
  name: "HomeView",
  components: {
    HeaderStore,
    HeroStore,
    WomenProduct,
    InstaProduct,
    PartnerStore,
    FooterStore,
  },
};
</script>
