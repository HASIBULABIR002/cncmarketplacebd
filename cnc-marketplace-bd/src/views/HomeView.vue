<script setup lang="ts">
import TheWelcome from '../components/TheWelcome.vue'
</script>

<template>
  <div class="min-h-screen bg-base-200">
    <nav class="p-4 bg-base-100 shadow-sm">
      <!-- Add language toggle later -->
    </nav>
    
    <main>
      <TheWelcome />
    </main>

    <div class="hero-content text-center">
      <div class="max-w-2xl">
        <h1 class="text-5xl font-bold mb-4">CNC Marketplace BD</h1>
        <p class="mb-6">বাংলাদেশের প্রথম সুরক্ষিত CNC ডিজাইন বাণিজ্য প্ল্যাটফর্ম</p>
        <div class="flex gap-4 justify-center">
          <button class="btn btn-primary">Designer Signup</button>
          <button class="btn btn-secondary">Buyer Signup</button>
        </div>
      </div>
    </div>
  </div>
</template>
