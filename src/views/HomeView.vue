<template>
  <v-app>
    <AppNav />
    <AppCarousel />
    <AppServices />
    <AppFrameworks />
    <AppSocials />
    <AppFooter />
  </v-app>
</template>

<script>
import appNav from "@/components/NavBar";
import appCarousel from "@/components/CarouSel";
import appServices from "@/components/ServiCes";
import appFramworks from "@/components/FramWorks";
import appSocials from "@/components/SocialMedia";
import appFooter from "@/components/FooTer";
export default {
  name: "App",
  metaInfo: {
    title: "Devmedia",
    titleTemplate: "%s | Home ",
  },
  data: () => ({
    //
  }),

  components: {
    AppNav: appNav,
    AppCarousel: appCarousel,
    AppServices: appServices,
    AppFrameworks: appFramworks,
    AppSocials: appSocials,
    AppFooter: appFooter,
  },
};
</script>
