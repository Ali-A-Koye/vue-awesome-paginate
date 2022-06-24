<script setup lang="ts">
import vueAwesomePaginate from "./components/vue-awesome-paginate.vue";
</script>

<template>
  <vue-awesome-paginate
    :total-items="80"
    :itemsPerPage="5"
    :max-pages-shown="7"
    :current-page="1"
  />
</template>

<style></style>
