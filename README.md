<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>$PRO GO 10M MARKETCAP Frame</title>

    <!-- Script Tailwind CSS untuk styling halaman fallback (opsional) -->
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        body { font-family: 'Inter', sans-serif; }
    </style>

    <!-- Farcaster Frame Specific Tags -->
    <meta property="fc:frame" content="vNext" />

    <!-- Gambar untuk Frame -->
    <!-- Anda bisa mengganti URL gambar ini dengan gambar kustom Anda. -->
    <!-- Ukuran ideal sekitar 1.91:1 (misalnya 1200x630px) atau 1:1 (misalnya 800x800px) -->
    <meta property="fc:frame:image" content="https://placehold.co/1200x630/0000FF/FFFFFF?text=%24PRO%20GO%0A10M%20MARKETCAP&font=inter" />
    <meta property="fc:frame:image:aspect_ratio" content="1.91:1" />

    <!-- Tombol untuk Frame -->
    <!-- Tombol ini akan mengarahkan pengguna untuk membuat cast baru -->
    <meta property="fc:frame:button:1" content="📢 Bagikan & Dukung $PRO!" />
    <meta property="fc:frame:button:1:action" content="link" />
    <!--
        GANTI BAGIAN BERIKUT:
        1. @USERNAME_ANDA_DI_FARCASTER dengan username Farcaster Anda (tanpa @, tapi %40 digunakan untuk URL encoding @).
        2. https://URL_HOSTING_FRAME_ANDA/pro-frame.html dengan URL publik tempat Anda mengunggah file HTML ini.
           Ini penting agar ketika dibagikan, frame ini juga ikut tersemat.
    -->
    <meta property="fc:frame:button:1:target"
          content="https://warpcast.com/~/compose?text=%24PRO%20GO%2010M%20MARKETCAP%20%F0%9F%9A%80%0A%0ADukung%20bersama%20%40USERNAME_ANDA_DI_FARCASTER!&embeds[]=https://URL_HOSTING_FRAME_ANDA/pro-frame.html" />

    <!-- (Opsional) fc:frame:post_url jika Anda ingin menangani POST request -->
    <!-- Untuk kasus ini, karena hanya ada tombol 'link', post_url bisa mengarah kembali ke frame ini sendiri atau endpoint yang mengembalikan frame ini. -->
    <!-- Ganti https://URL_HOSTING_FRAME_ANDA/pro-frame.html dengan URL publik file HTML ini. -->
    <meta property="fc:frame:post_url" content="https://URL_HOSTING_FRAME_ANDA/pro-frame.html" />


    <!-- Fallback Open Graph tags (baik untuk preview di platform lain) -->
    <meta property="og:title" content="$PRO GO 10M MARKETCAP" />
    <meta property="og:description" content="Klik untuk membagikan dukungan untuk $PRO mencapai 10 Juta Marketcap di Farcaster!" />
    <meta property="og:image" content="https://placehold.co/1200x630/0000FF/FFFFFF?text=%24PRO%20GO%0A10M%20MARKETCAP&font=inter" />
    <meta property="og:url" content="https://URL_HOSTING_FRAME_ANDA/pro-frame.html" /> <!-- Ganti dengan URL publik file HTML ini -->
    <meta property="og:type" content="website" />

</head>
<body class="bg-gray-100 min-h-screen flex flex-col items-center justify-center text-center p-4">
    <div class="bg-white p-8 rounded-lg shadow-xl max-w-md w-full">
        <img src="https://placehold.co/600x315/0000FF/FFFFFF?text=%24PRO%20GO%0A10M%20MARKETCAP&font=inter" alt="$PRO GO 10M MARKETCAP" class="w-full rounded-md mb-6">
        <h1 class="text-2xl font-bold text-gray-800 mb-3">$PRO GO 10M MARKETCAP!</h1>
        <p class="text-gray-600 mb-6">
            Frame ini dirancang untuk Farcaster. Bagikan URL halaman ini di Farcaster untuk melihat frame beraksi.
            Mengklik tombol di frame akan membantu Anda membagikan pesan dukungan ini.
        </p>
        <a href="https://warpcast.com/~/compose?text=%24PRO%20GO%2010M%20MARKETCAP%20%F0%9F%9A%80%0A%0ADukung%20bersama%20%40USERNAME_ANDA_DI_FARCASTER!&embeds[]=https://URL_HOSTING_FRAME_ANDA/pro-frame.html"
           target="_blank"
           class="inline-block bg-blue-600 hover:bg-blue-700 text-white font-semibold py-3 px-6 rounded-lg transition duration-150 ease-in-out">
            Bagikan Dukungan Manual
        </a>
        <p class="text-xs text-gray-500 mt-6">
            Pastikan untuk mengganti placeholder <code>@USERNAME_ANDA_DI_FARCASTER</code> dan <code>https://URL_HOSTING_FRAME_ANDA/pro-frame.html</code> dalam kode sumber HTML.
        </p>
    </div>
</body>
</html>
