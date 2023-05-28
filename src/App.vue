<template>
  <MainLayout />
  <!-- <router-view /> -->
</template>

<script>
import { defineComponent } from 'vue'
import MainLayout from '@/components/MainLayout.vue'

export default defineComponent({
  name: 'App',
  components: {MainLayout}
})
</script>

<style></style>