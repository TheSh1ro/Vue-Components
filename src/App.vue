<script>
import MenuLateral from "@/components/MenuLateral.vue";
import PageHeader from "./components/PageHeader.vue";
import MainContainer from "./components/MainContainer.vue";
import PageFooter from "./components/PageFooter.vue";
export default {
  components: { MenuLateral, PageHeader, MainContainer, PageFooter },
};
</script>
<template>
  <PageHeader />
  <MenuLateral />
  <MainContainer />
  <PageFooter />
</template>
<style></style>
