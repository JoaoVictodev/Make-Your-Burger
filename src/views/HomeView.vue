<template>
  <Banner />
  <div class="main-container">
    <h1>Monter o seu burguer:</h1>
    <BurgeForm />
  </div>
</template>

<script>
import Banner from "@/components/Banner.vue";
import BurgeForm from "@/components/BurgeForm.vue";

export default {
  name: "HomeView",
  components: {
    Banner,
    BurgeForm,
  },
  
};
</script>
