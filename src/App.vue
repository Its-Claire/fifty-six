<script setup>
</script>

<template>
  <div class="min-h-screen bg-gray-50 flex flex-col">
    <!-- Header -->
    <header class="bg-white shadow-md">
      <div class="container mx-auto flex justify-between items-center py-5 px-6">
        <div class="flex items-center gap-3">
          <img src="./assets/vue.svg" alt="Company Logo" class="h-10 w-10" />
          <span class="text-2xl font-bold text-gray-800 tracking-wide">IT Solution Co.</span>
        </div>
        <nav class="space-x-8 hidden md:block">
          <a href="#services" class="text-gray-700 hover:text-blue-600 font-medium transition">Layanan</a>
          <a href="#about" class="text-gray-700 hover:text-blue-600 font-medium transition">Tentang Kami</a>
          <a href="#contact" class="text-gray-700 hover:text-blue-600 font-medium transition">Kontak</a>
        </nav>
      </div>
    </header>

    <!-- Hero Section -->
    <section class="bg-gradient-to-r from-blue-600 to-teal-400 text-white py-20 px-6">
      <div class="container mx-auto text-center max-w-2xl">
        <h1 class="text-4xl md:text-5xl font-extrabold mb-6 leading-tight drop-shadow-lg">
          Solusi IT Terbaik untuk Bisnis Anda
        </h1>
        <p class="text-lg md:text-xl mb-8 font-light">
          Kami menyediakan layanan pengembangan perangkat lunak, konsultasi IT, dan transformasi digital untuk mendukung pertumbuhan bisnis Anda.
        </p>
        <a href="#contact" class="inline-block bg-white text-blue-600 font-semibold px-8 py-3 rounded-full shadow-lg hover:bg-blue-50 transition">
          Hubungi Kami
        </a>
      </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="py-20 bg-gray-50">
      <div class="container mx-auto px-6">
        <h2 class="text-3xl font-bold text-center text-gray-800 mb-12">Layanan Kami</h2>
        <div class="grid gap-8 md:grid-cols-3">
          <div class="bg-white rounded-xl shadow-lg p-8 hover:shadow-2xl transition">
            <div class="flex items-center justify-center mb-4">
              <span class="inline-flex items-center justify-center w-14 h-14 rounded-full bg-blue-100 text-blue-600 text-3xl">
                <i class="fas fa-laptop-code"></i>
              </span>
            </div>
            <h3 class="text-xl font-semibold mb-2 text-gray-800">Pengembangan Web</h3>
            <p class="text-gray-600">Membangun website modern, responsif, dan aman sesuai kebutuhan bisnis Anda.</p>
          </div>
          <div class="bg-white rounded-xl shadow-lg p-8 hover:shadow-2xl transition">
            <div class="flex items-center justify-center mb-4">
              <span class="inline-flex items-center justify-center w-14 h-14 rounded-full bg-teal-100 text-teal-600 text-3xl">
                <i class="fas fa-user-tie"></i>
              </span>
            </div>
            <h3 class="text-xl font-semibold mb-2 text-gray-800">Konsultasi IT</h3>
            <p class="text-gray-600">Memberikan solusi dan strategi IT terbaik untuk efisiensi dan inovasi.</p>
          </div>
          <div class="bg-white rounded-xl shadow-lg p-8 hover:shadow-2xl transition">
            <div class="flex items-center justify-center mb-4">
              <span class="inline-flex items-center justify-center w-14 h-14 rounded-full bg-purple-100 text-purple-600 text-3xl">
                <i class="fas fa-sync-alt"></i>
              </span>
            </div>
            <h3 class="text-xl font-semibold mb-2 text-gray-800">Transformasi Digital</h3>
            <p class="text-gray-600">Membantu bisnis Anda beradaptasi dengan teknologi terbaru untuk daya saing maksimal.</p>
          </div>
        </div>
      </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-20 bg-white">
      <div class="container mx-auto px-6 max-w-3xl text-center">
        <h2 class="text-3xl font-bold text-gray-800 mb-6">Tentang Kami</h2>
        <p class="text-gray-600 text-lg">
          IT Solution Co. adalah perusahaan teknologi yang berfokus pada pengembangan solusi digital inovatif untuk berbagai industri. Dengan tim profesional berpengalaman, kami siap membantu bisnis Anda tumbuh melalui teknologi.
        </p>
      </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-20 bg-gray-50">
      <div class="container mx-auto px-6 max-w-2xl text-center">
        <h2 class="text-3xl font-bold text-gray-800 mb-6">Kontak</h2>
        <p class="text-gray-600 mb-8">Email: <a href="mailto:info@itsolution.co" class="text-blue-600 hover:underline">info@itsolution.co</a> | Telepon: <a href="tel:081234567890" class="text-blue-600 hover:underline">0812-3456-7890</a></p>
        <form class="space-y-6">
          <div>
            <input type="text" placeholder="Nama Anda" class="w-full px-5 py-3 rounded-lg border border-gray-300 focus:ring-2 focus:ring-blue-400 outline-none" />
          </div>
          <div>
            <input type="email" placeholder="Email" class="w-full px-5 py-3 rounded-lg border border-gray-300 focus:ring-2 focus:ring-blue-400 outline-none" />
          </div>
          <div>
            <textarea placeholder="Pesan" rows="4" class="w-full px-5 py-3 rounded-lg border border-gray-300 focus:ring-2 focus:ring-blue-400 outline-none"></textarea>
          </div>
          <button type="submit" class="w-full bg-blue-600 text-white font-semibold py-3 rounded-lg hover:bg-blue-700 transition">Kirim Pesan</button>
        </form>
      </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-800 text-gray-200 text-center py-6 mt-auto">
      &copy; 2025 IT Solution Co. All rights reserved.
    </footer>
  </div>
</template>

<style scoped>
</style>
