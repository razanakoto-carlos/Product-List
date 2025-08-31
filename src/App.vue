<script setup>
import Card from './components/Card.vue'
import Chart from './components/Chart.vue'
import data from './data/data.json'
</script>

<template>
  <div class="min-h-screen bg-[#fdf8f6] p-6">
    <div class="max-w-7xl mx-auto grid grid-cols-1 md:grid-cols-3 lg:grid-cols-4 gap-6">
      <div class="md:col-span-2 lg:col-span-3">
        <h1 class="text-3xl font-bold mt-4 mb-2">Desserts</h1>
        <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 gap-6">
          <Card /> <Card /> <Card />
        </div>
      </div>
      <div><Chart /></div>
    </div>
  </div>
</template>

<style scoped></style>
