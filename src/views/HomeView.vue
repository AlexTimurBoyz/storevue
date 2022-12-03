<template>
  <div class="home">
    <headerKu />
    <HeroView />
    <WomenView />
    <InstaView />
    <XpatnerView />
    <FooterView/>

   
  </div>
</template>

<script>
// @ is an alias to /src
import headerKu from "@/components/HeaderView.vue";
import HeroView from "@/components/HeroView.vue";
import WomenView from "@/components/WomenView.vue";
import InstaView from "@/components/InstagramView.vue";
import XpatnerView from "@/components/XpatnerView.vue";
import FooterView from "@/components/FooterView.vue";





export default {
  name: "HomeView",
  components: {
    headerKu,
    HeroView,
    WomenView,
    InstaView,
    XpatnerView,
    FooterView,

    
   
  },
};
</script>
