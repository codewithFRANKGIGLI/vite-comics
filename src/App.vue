    <script>
      import { AppHeader } from "AppHeader.vue";
      import { AppMainContent } from "AppMainContent.vue";
      import { AppFeatures } from "AppFeatures.vue";
      import { AppTopFooter } from "AppTopFooter.vue";
      import { AppBottomFooter } from "AppBottomFooter.vue";
      export default {
        AppHeader,
        AppMainContent,
        AppFeatures,
        AppTopFooter,
        AppBottomFooter,
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

<style lang="scss" scoped>

</style>