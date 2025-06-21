<template>
  <div class="bg-gray-900 text-white py-10">
    <div class="mx-auto px-4 grid grid-cols-1 md:grid-cols-3 gap-8 text-center md:text-left">
      <!-- Column 1 -->
      <div>
        <h3 class="text-xl font-semibold mb-4">Wal-Track</h3>
        <p class="text-gray-400">Take charge of your finances with smart tracking tools and insights.</p>
      </div>

      <!-- Column 2 -->
      <div>
        <h3 class="text-xl font-semibold mb-4">Quick Links</h3>
        <ul class="space-y-2 text-gray-400">
          <li><a href="#" class="hover:text-white transition">Home</a></li>
          <li><a href="#" class="hover:text-white transition">Features</a></li>
          <li><a href="#" class="hover:text-white transition">Pricing</a></li>
          <li><a href="#" class="hover:text-white transition">Contact</a></li>
        </ul>
      </div>

      <!-- Column 3 -->
      <div>
        <h3 class="text-xl font-semibold mb-4">Follow Us</h3>
        <div class="flex justify-center md:justify-start gap-4 text-gray-400">
          <a href="#" class="hover:text-white transition">🌐</a>
          <a href="#" class="hover:text-white transition">🐦</a>
          <a href="#" class="hover:text-white transition">📘</a>
        </div>
      </div>
    </div>

    <div class="mt-10 border-t border-gray-700 pt-4 text-center text-sm text-gray-500">
      © {{ new Date().getFullYear() }} Wal-Track. All rights reserved.
    </div>
  </div>
</template>

<!-- <script setup>
// Nothing needed unless you're dynamically injecting links
</script> -->
