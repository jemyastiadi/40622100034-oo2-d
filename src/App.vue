<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import LeftNav from '@/components/navbar/LeftNav.vue'
import MhsForm from '@/components/MahasiswaForm.vue'
import DosenForm from '@/components/DosenForm.vue'
import RuanganForm from '@/components/RuanganForm.vue'
</script>

<template>
  <v-layout class="rounded rounded-md">
    <v-app-bar title="Aplikasi penjadwalan kuliah"></v-app-bar>

    <LeftNav></LeftNav>

    <v-main class="d-flex align-center justify-center" style="min-height: 300px">
      <RouterView></RouterView>
    </v-main>
  </v-layout>
</template>
