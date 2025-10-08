# karista-Reyza-Yapira
we sale gantungan unik
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ganci Unik Lucu - Kelas XII.H Kelompok 4</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Poppins', sans-serif;
        }
        .hero-bg {
            background-color: #fce4ec; /* Light Pink */
            background-image: linear-gradient(to right top, #fce4ec, #f8e7f3, #f4eaf8, #f1edfc, #f0f0ff, #e9f2ff, #e2f4ff, #dcf6ff, #d2f6fa, #cbf5f1, #c8f3e6, #c9f1da);
        }
        .btn-primary {
            background-color: #00bfff; /* Deep Sky Blue */
            color: white;
            transition: background-color 0.3s ease;
        }
        .btn-primary:hover {
            background-color: #009acd;
        }
        .section-title {
            color: #ff69b4; /* Hot Pink */
        }
        .card {
            box-shadow: 0 4px 6px -1px rgb(0 0 0 / 0.1), 0 2px 4px -2px rgb(0 0 0 / 0.1);
            border-radius: 1rem;
            transition: transform 0.3s ease;
        }
        .card:hover {
            transform: translateY(-5px);
        }
        nav a {
            transition: color 0.3s ease;
        }
        nav a:hover {
            color: #ff69b4; /* Hot Pink */
        }
    </style>
</head>
<body class="bg-white text-gray-800">

    <!-- Header / Navigation -->
    <header class="bg-white shadow-md sticky top-0 z-50">
        <nav class="container mx-auto px-6 py-4 flex justify-between items-center">
            <a href="#" class="text-2xl font-bold text-pink-500">Ganci Unik</a>
            <div class="hidden md:flex space-x-8">
                <a href="#beranda" class="font-semibold">Beranda</a>
                <a href="#tentang" class="font-semibold">Tentang Kami</a>
                <a href="#layanan" class="font-semibold">Pilihan Ganci</a>
                <a href="#testimoni" class="font-semibold">Testimoni</a>
                <a href="#pesan" class="font-semibold">Pesan Sekarang</a>
            </div>
            <div class="md:hidden">
                <button id="menu-btn" class="text-gray-800 focus:outline-none">
                    <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16m-7 6h7"></path></svg>
                </button>
            </div>
        </nav>
        <!-- Mobile Menu -->
        <div id="mobile-menu" class="hidden md:hidden">
            <a href="#beranda" class="block py-2 px-4 text-sm hover:bg-pink-50">Beranda</a>
            <a href="#tentang" class="block py-2 px-4 text-sm hover:bg-pink-50">Tentang Kami</a>
            <a href="#layanan" class="block py-2 px-4 text-sm hover:bg-pink-50">Pilihan Ganci</a>
            <a href="#testimoni" class="block py-2 px-4 text-sm hover:bg-pink-50">Testimoni</a>
            <a href="#pesan" class="block py-2 px-4 text-sm hover:bg-pink-50">Pesan Sekarang</a>
        </div>
    </header>

    <!-- Main Content -->
    <main>
        <!-- Beranda / Hero Section -->
        <section id="beranda" class="hero-bg">
            <div class="container mx-auto px-6 py-20 flex flex-col md:flex-row items-center">
                <div class="md:w-1/2 text-center md:text-left mb-10 md:mb-0">
                    <h1 class="text-4xl md:text-5xl font-bold text-gray-800 leading-tight">Gantungan Kunci Unik & Lucu Buatan Kami!</h1>
                    <p class="mt-4 text-lg text-gray-600">Projek kewirausahaan dari Kelas XII.H Kelompok 4. Dapatkan ganci estetik dengan desain yang bisa kamu pilih sendiri!</p>
                    <a href="#pesan" class="mt-8 inline-block btn-primary font-bold py-3 px-8 rounded-full">Pesan Sekarang</a>
                </div>
                <div class="md:w-1/2">
                    <img src="https://placehold.co/600x400/FFC0CB/333333?text=Ganci+Unik+%26+Lucu" alt="[Gambar Berbagai Macam Gantungan Kunci Unik dan Lucu]" class="rounded-lg shadow-2xl w-full">
                </div>
            </div>
        </section>

        <!-- Tentang Kami -->
        <section id="tentang" class="py-20">
            <div class="container mx-auto px-6 text-center">
                <h2 class="text-3xl font-bold section-title mb-4">Tentang Kami</h2>
                <div class="w-24 h-1 bg-pink-400 mx-auto mb-8"></div>
                <p class="max-w-3xl mx-auto text-gray-600">
                    Hai semua! Kami adalah Kelompok 4 dari kelas XII.H yang sedang menjalankan projek kewirausahaan. Kami percaya bahwa barang kecil seperti gantungan kunci bisa jadi penyemangat dan nunjukkin kepribadianmu. Makanya, kami buat ganci unik yang lucu dan berkualitas tinggi, cocok banget buat para pelajar dan remaja kayak kita. Setiap pembelianmu sangat berarti untuk mendukung projek kami. Terima kasih!
                </p>
            </div>
        </section>

        <!-- Layanan / Pilihan Ganci -->
        <section id="layanan" class="bg-gray-50 py-20">
            <div class="container mx-auto px-6">
                <div class="text-center mb-12">
                    <h2 class="text-3xl font-bold section-title mb-4">Pilihan Ganci & Harga</h2>
                    <p class="text-gray-600">Pilih ukuran yang paling pas buat kamu!</p>
                </div>
                <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                    <!-- Ukuran Kecil -->
                    <div class="card bg-white p-8 text-center">
                        <img src="https://placehold.co/100x100/87CEEB/FFFFFF?text=S" alt="[Gambar Ganci Ukuran Kecil]" class="mx-auto mb-4 rounded-full">
                        <h3 class="text-xl font-bold text-gray-800 mb-2">Ukuran Kecil</h3>
                        <p class="text-3xl font-bold text-blue-500 mb-4">Rp 7.000</p>
                        <p class="text-gray-600">Praktis dan imut, cocok untuk kunci motor atau tas kecil.</p>
                    </div>
                    <!-- Ukuran Sedang -->
                    <div class="card bg-white p-8 text-center border-4 border-pink-400">
                         <img src="https://placehold.co/100x100/FFB6C1/FFFFFF?text=M" alt="[Gambar Ganci Ukuran Sedang]" class="mx-auto mb-4 rounded-full">
                        <h3 class="text-xl font-bold text-gray-800 mb-2">Ukuran Sedang</h3>
                        <p class="text-3xl font-bold text-pink-500 mb-4">Rp 10.000</p>
                        <p class="text-gray-600">Paling populer! Ukuran pas dengan detail yang lebih jelas.</p>
                    </div>
                    <!-- Ukuran Besar -->
                    <div class="card bg-white p-8 text-center">
                        <img src="https://placehold.co/100x100/87CEFA/FFFFFF?text=L" alt="[Gambar Ganci Ukuran Besar]" class="mx-auto mb-4 rounded-full">
                        <h3 class="text-xl font-bold text-gray-800 mb-2">Ukuran Besar</h3>
                        <p class="text-3xl font-bold text-blue-500 mb-4">Rp 15.000</p>
                        <p class="text-gray-600">Jadi pusat perhatian! Cocok untuk digantung di tas ransel.</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Testimoni Pelanggan -->
        <section id="testimoni" class="py-20">
            <div class="container mx-auto px-6">
                <div class="text-center mb-12">
                    <h2 class="text-3xl font-bold section-title mb-4">Kata Mereka</h2>
                    <p class="text-gray-600">Cerita dari teman-teman yang sudah punya ganci kami.</p>
                </div>
                <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                    <div class="card bg-white p-8">
                        <p class="text-gray-600 italic mb-4">"Sumpah gancinya lucu banget! Desainnya kekinian dan pas buat anak sekolah. Temen-temenku langsung pada nanyain beli di mana. Recommended!"</p>
                        <div class="flex items-center">
                            <img src="https://placehold.co/50x50/F0F8FF/333?text=A" class="rounded-full mr-4" alt="[Avatar Pelanggan]">
                            <div>
                                <p class="font-bold">Amanda Putri</p>
                                <p class="text-sm text-gray-500">Pelajar SMA</p>
                            </div>
                        </div>
                    </div>
                    <div class="card bg-white p-8">
                        <p class="text-gray-600 italic mb-4">"Proses pesannya gampang dan cepet. Kualitasnya juga oke banget, nggak murahan. Suka deh sama warnanya yang cerah. Sukses terus ya, Kelompok 4!"</p>
                        <div class="flex items-center">
                            <img src="https://placehold.co/50x50/FFE4E1/333?text=R" class="rounded-full mr-4" alt="[Avatar Pelanggan]">
                            <div>
                                <p class="font-bold">Rizky Pratama</p>
                                <p class="text-sm text-gray-500">Siswa SMP</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Formulir Pemesanan -->
        <section id="pesan" class="bg-gray-50 py-20">
            <div class="container mx-auto px-6">
                <div class="text-center mb-12">
                    <h2 class="text-3xl font-bold section-title mb-4">Yuk, Pesan Gancimu!</h2>
                    <p class="text-gray-600">Isi form di bawah ini dan kami akan segera menghubungimu.</p>
                </div>
                <div class="flex flex-col md:flex-row gap-12">
                    <!-- Form -->
                    <div class="w-full md:w-1/2 bg-white p-8 rounded-lg shadow-lg">
                        <form id="order-form">
                            <div class="mb-4">
                                <label for="nama" class="block text-gray-700 font-bold mb-2">Nama Lengkap</label>
                                <input type="text" id="nama" name="nama" class="w-full px-3 py-2 border border-gray-300 rounded-lg focus:outline-none focus:border-pink-500" placeholder="Nama kamu" required>
                            </div>
                            <div class="mb-4">
                                <label for="kontak" class="block text-gray-700 font-bold mb-2">Nomor WhatsApp</label>
                                <input type="text" id="kontak" name="kontak" class="w-full px-3 py-2 border border-gray-300 rounded-lg focus:outline-none focus:border-pink-500" placeholder="08..." required>
                            </div>
                             <div class="mb-4">
                                <label for="pilihan" class="block text-gray-700 font-bold mb-2">Pilih Ukuran</label>
                                <select id="pilihan" name="pilihan" class="w-full px-3 py-2 border border-gray-300 rounded-lg focus:outline-none focus:border-pink-500" required>
                                    <option value="">-- Pilih Ganci --</option>
                                    <option value="Kecil - Rp 7.000">Kecil - Rp 7.000</option>
                                    <option value="Sedang - Rp 10.000">Sedang - Rp 10.000</option>
                                    <option value="Besar - Rp 15.000">Besar - Rp 15.000</option>
                                </select>
                            </div>
                            <div class="mb-6">
                                <label for="jumlah" class="block text-gray-700 font-bold mb-2">Jumlah</label>
                                <input type="number" id="jumlah" name="jumlah" class="w-full px-3 py-2 border border-gray-300 rounded-lg focus:outline-none focus:border-pink-500" value="1" min="1" required>
                            </div>
                            <button type="submit" class="w-full btn-primary font-bold py-3 px-6 rounded-full">Kirim Pesanan</button>
                        </form>
                    </div>
                    <!-- Payment Info -->
                    <div class="w-full md:w-1/2">
                        <h3 class="text-2xl font-bold text-gray-800 mb-4">Metode Pembayaran</h3>
                        <p class="text-gray-600 mb-6">Setelah mengirim form, silakan lakukan pembayaran melalui salah satu metode di bawah ini dan kirim bukti transfer ke WhatsApp kami.</p>
                        
                        <div class="bg-white p-6 rounded-lg shadow-lg mb-6">
                            <h4 class="font-bold text-lg mb-2">Via WhatsApp</h4>
                            <p class="text-gray-700">Kirim pesan konfirmasi ke:</p>
                            <p class="text-blue-600 font-semibold text-xl">0896-3776-1388</p>
                        </div>

                        <div class="bg-white p-6 rounded-lg shadow-lg">
                            <h4 class="font-bold text-lg mb-2">Via DANA</h4>
                            <p class="text-gray-700 mb-4">Scan QR Code di bawah ini:</p>
                            <img src="https://placehold.co/250x250/ffffff/000000?text=Scan+QR+DANA" alt="[QR Code untuk Pembayaran DANA]" class="mx-auto md:mx-0 rounded-md">
                            <p class="text-center md:text-left mt-2 text-gray-600 font-semibold">a.n. Kelompok 4</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>
    </main>
    
    <!-- Footer -->
    <footer class="bg-gray-800 text-white py-8">
        <div class="container mx-auto px-6 text-center">
            <p>&copy; 2025 Ganci Unik Lucu. Dibuat oleh Kelas XII.H Kelompok 4.</p>
        </div>
    </footer>
    
    <script>
        // Mobile menu toggle
        const menuBtn = document.getElementById('menu-btn');
        const mobileMenu = document.getElementById('mobile-menu');
        menuBtn.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });

        // Form submission to WhatsApp
        const orderForm = document.getElementById('order-form');
        orderForm.addEventListener('submit', function(e) {
            e.preventDefault();
            
            const nama = document.getElementById('nama').value;
            const kontak = document.getElementById('kontak').value;
            const pilihan = document.getElementById('pilihan').value;
            const jumlah = document.getElementById('jumlah').value;

            const message = `Halo, saya mau pesan ganci unik!
Nama: ${nama}
No. WA: ${kontak}
Pilihan: ${pilihan}
Jumlah: ${jumlah}

Terima kasih!`;

            const whatsappURL = https://api.whatsapp.com/send?phone=6289637761388&text=${encodeURIComponent(message)};

            window.open(whatsappURL, '_blank');
        });
    </script>
