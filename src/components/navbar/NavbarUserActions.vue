<script setup lang="ts">
import IconTooling from '../icons/IconTooling.vue';



</script>

<template>
  <div class="navbar-user-actions">
    <span>FR</span>
    <span><IconTooling /></span>
    <span><IconTooling /></span>
  </div>
</template>

<style scoped>
.navbar-user-actions {
    display: flex;
}

.navbar-user-actions > * {
  padding: 0 5px;
}

.navbar-user-actions > *:not(:last-child) {
    border-right: 1px solid grey;
}
</style>
