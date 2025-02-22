<template>
    <!-- Global Container -->
    <div class="container mx-auto max-w-7xl p-2 md:p-10">
      <!-- Box 1 -->
      <div class="p-10 rounded-xl bg-purple-700 text-white">
  
      <!-- Flex Container -->
      <div class="flex space-x-4">
        <div class="text-sm">
          <h4 class="opacity-90">Contributor</h4>
          <h4 class="opacity-90">Date</h4>
           <!-- Large Text -->
      <p class="mt-6 text-xl">{{ casino.name }}</p>
      <p class="mt-6 text-xl">{{ casino.title }}</p>
      <p class="mt-6 text-xl">{{ casino.location }}</p>
      <p class="mt-6 text-xl">{{ casino.message }}</p>
      </div>
        </div>
      </div>
  
     
    </div>
  </template>
  
  <script setup>
  // Dummy casino data (replace this with API data later)
  const casino = {
    name: "Casino Royale",
    title: "High Stakes Night",
    location: "Las Vegas",
    message: "Join us for an unforgettable night of poker and blackjack."
  };
  </script>
  
  <style lang="scss" scoped>
  </style>
  