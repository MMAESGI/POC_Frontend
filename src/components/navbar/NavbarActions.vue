<script setup lang="ts">
import IconTooling from '../icons/IconTooling.vue';

</script>

<template>
  <div class="navbar-actions">
    <span><IconTooling />Paris</span>
    <span><IconTooling />Catégories</span>
    <span><IconTooling />Carte</span>
  </div>
</template>

<style scoped>
.navbar-actions {
    display: flex;
    align-items: center;
    justify-content: space-between;
}

.navbar-actions > * {
  padding: 0 3%;
  display: flex;
}
.navbar-actions > *:not(:last-child) {
    border-right: 1px solid grey;
}
</style>
