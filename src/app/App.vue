<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import { PlaygroundPage } from '@/pages'

const tmp = 2
</script>

<template>
  <RouterView />

  <div v-for="item in items" :key="item">item</div>
</template>

<style scoped></style>
