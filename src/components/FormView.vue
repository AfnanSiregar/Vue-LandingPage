<template>
  <section class="py-16" id="formview">
    <div class="flex items-center justify-center flex-col">
        <div class="text-center py-5">
            <p class="text-2xl font-semibold text-black">
                Dapatkan Perlindungan <a href="#" class="text-blue-900">AXA Protection</a> Sekarang
            </p>
            <p class="font-semibold">Cukup isi data diri Anda pada form dibawah ini</p>
        </div>
        <form>
        <div class="mb-6">
            <label for="fullname" class="block mb-2 text-black font-semibold">Nama Lengkap</label>
            <input type="text" id="fullname" class="bg-white border-2 border-purple-300 rounded text-gray-700 w-full p-2.5" required>
        </div>
        <div class="mb-6">
            <label for="birthday" class="block mb-2 text-black font-semibold">Tanggal Lahir (dd/mm/yyyy)</label>
            <input type="date" id="birthday" class="bg-white border-2 border-purple-300 rounded text-gray-700 w-full p-2.5" required>
        </div>
        <div class="mb-6">
            <label for="email" class="block mb-2 text-black font-semibold">Email</label>
            <input type="email" id="email" class="bg-white border-2 border-purple-300 rounded text-gray-700 w-full p-2.5" required>
        </div>
        <div class="mb-6">
            <label for="phone" class="block mb-2 text-black font-semibold">Nomor Ponsel</label>
            <input type="number" id="phone" class="bg-white border-2 border-purple-300 rounded text-gray-700 w-full p-2.5" required>
        </div>
        <div class="mb-6">
            <p class="block mb-2 text-black font-semibold">Memiliki Kartu Kredit</p>
            <label for="visa">
                <input type="checkbox" id="visa" class="bg-white border-2 border-purple-300 rounded text-gray-700 focus:outline-none">
                Visa
            </label>
            <label for="masterc">
                <input type="checkbox" id="masterc" class="bg-white border-2 border-purple-300 rounded text-gray-700 focus:outline-none">
                MASTER CARD
            </label>
            <label for="bca">
                <input type="checkbox" id="bca" class="bg-white border-2 border-purple-300 rounded text-gray-700 focus:outline-none">
                BCA CARD
            </label>
            <label for="other">
                <input type="checkbox" id="other" class="bg-white border-2 border-purple-300 rounded text-gray-700 focus:outline-none">
                Lainnya
            </label>
            <div class="text-justify pt-6">
                <i class="text-black underline">  
                    Syarat & Ketentuan Aplikasi
                </i>
                <label for="agree">
                    <p class="text-sm text-justify">
                        <input type="checkbox" id="agree" class="bg-white border-2 border-purple-300 rounded text-gray-700 focus:outline-none">
                        Saya mengetahui dan menyetujui syarat dan ketentuan diatas serta bersedia dihubungi oleh PT. AXA
                        Life Indonesia <br> untuk mendapatkan penjelasan tentang produk dan informasi lainnya
                    </p>
                </label>
            </div>
        </div>
        <button type="submit" class="bg-blue-900 text-white rounded px-14 py-2">Kirim</button>
        </form>

    </div>
  </section>
</template>

<script>
export default {

}
</script>

<style>

</style>