<template>
    <section id="contact" class="py-20 bg-gray-50">
        <div class="container mx-auto px-6 max-w-2xl text-center">
            <h2 class="text-3xl font-bold text-gray-800 mb-6">Kontak</h2>
            <p class="text-gray-600 mb-8">Email: <a href="mailto:info@fiftysix.co" class="text-blue-600 hover:underline">info@fiftysix.co</a> | Telepon: <a href="tel:081234567890" class="text-blue-600 hover:underline">0812-3456-7890</a></p>
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
</template>