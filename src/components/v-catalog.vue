<template>
  <div class="v-catalog">
    <h1>Catalog</h1>
    <v-catalog-item />
  </div>
</template>

<script>
import vCatalogItem from "./v-catalog-item.vue";

export default {
  name: "v-catalog",
  components: {
    vCatalogItem,
  },
};
</script>

<style lang="scss">
.v-catalog {
  &__list {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    align-items: center;
  }
}
</style>
