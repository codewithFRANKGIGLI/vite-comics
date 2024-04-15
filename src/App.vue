<script>
  import AppHeader from "./components/AppHeader.vue";
  import AppMainContent from "./components/AppMainContent.vue";
  import AppFeatures from "./components/AppFeatures.vue";
  import AppTopFooter from "./components/AppTopFooter.vue";
  import AppBottomFooter from "./components/AppBottomFooter.vue";
  export default {
    components: {
      AppHeader,
      AppMainContent,
      AppFeatures,
      AppTopFooter,
      AppBottomFooter,
    }
  }
</script>

<template>
  <div>
    <AppHeader></AppHeader>
    <AppMainContent></AppMainContent>
    <AppFeatures></AppFeatures>
    <AppTopFooter></AppTopFooter>
    <AppBottomFooter></AppBottomFooter>
  </div>
</template>

<style lang="scss">

</style>