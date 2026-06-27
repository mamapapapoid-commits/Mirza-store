<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Digital Store | Store Mirza</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        body {
            background: #0a0f1e;
            background-image: radial-gradient(circle at top, #1e293b 0%, #0a0f1e 60%);
            color: #ffffff;
            min-height: 100vh;
            padding: 24px 16px 60px;
        }
        .wrapper {
            max-width: 600px;
            margin: 0 auto;
            text-align: center;
        }
        h1 {
            font-size: clamp(2.2rem, 10vw, 3rem);
            font-weight: 800;
            background: linear-gradient(90deg, #22d3ee, #38bdf8);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
            margin-bottom: 12px;
            letter-spacing: -1px;
        }
        .subtitle {
            font-size: 0.95rem;
            color: #94a3b8;
            line-height: 1.6;
            max-width: 500px;
            margin: 0 auto 40px;
        }
        h2 {
            font-size: 1.8rem;
            font-weight: 700;
            margin-bottom: 28px;
        }
        .grid {
            display: grid;
            gap: 20px;
        }
        .card {
            background: rgba(15, 23, 42, 0.6);
            border: 1px solid rgba(56, 189, 248, 0.2);
            border-radius: 24px;
            padding: 28px 20px;
            backdrop-filter: blur(10px);
            transition: all 0.3s ease;
        }
        .card:hover {
            border-color: #38bdf8;
            box-shadow: 0 0 25px rgba(56, 189, 248, 0.25);
            transform: translateY(-4px);
        }
        .card.highlight {
            border: 2px solid #22d3ee;
            box-shadow: 0 0 30px rgba(34, 211, 238, 0.3);
        }
        .icon {
            font-size: 3.2rem;
            margin-bottom: 16px;
            display: block;
        }
        .card h3 {
            font-size: 1.3rem;
            font-weight: 700;
            margin-bottom: 12px;
        }
        .card p {
            font-size: 0.9rem;
            color: #94a3b8;
            line-height: 1.6;
            margin-bottom: 20px;
        }
        .btn {
            display: inline-block;
            padding: 12px 32px;
            background: linear-gradient(135deg, #22d3ee, #06b6d4);
            color: #0a0f1e;
            font-weight: 700;
            font-size: 0.95rem;
            border-radius: 999px;
            border: none;
            cursor: pointer;
            text-decoration: none;
            transition: all 0.2s ease;
            box-shadow: 0 6px 20px rgba(34, 211, 238, 0.4);
        }
        .btn:hover {
            transform: scale(1.05);
            box-shadow: 0 8px 25px rgba(34, 211, 238, 0.6);
        }
    </style>
</head>
<body>

<div class="wrapper">
    <h1>Digital Store</h1>
    <p class="subtitle">Solusi kebutuhan digital instan, aman, dan bergaransi untuk menunjang kebutuhan harian maupun bisnismu.</p>

    <h2>Layanan Terbaik Kami</h2>

    <div class="grid" id="productGrid">
        <!-- Card akan di-generate JS -->
    </div>
</div>

<script>
    const noWa = '6285187588969'; // 

    const products = [
        { icon: '📱', title: 'Nokos (Nomor Kosong)', desc: 'Menyediakan nomor kosong siap pakai untuk verifikasi OTP berbagai aplikasi (WhatsApp, Telegram, dll). Proses instan dan bergaransi.', highlight: true },
        { icon: '🚀', title: 'Suntik All Sosmed', desc: 'Jasa suntik followers, likes, views untuk semua platform sosial media. Aman, cepat, dan tanpa password.' },
        { icon: '👑', title: 'CapCut Pro 1 Bulan', desc: 'Akses semua fitur premium CapCut: tanpa watermark, template pro, dan export 4K. Akun private.' },
        { icon: '🎬', title: 'Alight Motion Premium 1 Tahun', desc: 'Alight Motion Premium full unlock 1 tahun. No watermark, semua preset, keyframe unlocked.' },
        { icon: '🎨', title: 'APK Buat Logo', desc: 'Aplikasi premium buat desain logo tanpa iklan. 1000+ template, export HD, no watermark.' },
        { icon: '💼', title: 'APK JB', desc: 'Aplikasi Jual Beli auto, injector, dan tools bisnis digital. Cocok buat reseller.' },
        { icon: '💳', title: 'APK QR No KTP (QR Merah)', desc: 'Aplikasi generate QR dana/gopay tanpa KTP. Praktis buat transaksi anonim.' },
        { icon: '🐛', title: 'Join Murbug via Telegram', desc: 'Akses grup murbug eksklusif di Telegram. Update bug, script, dan tools terbaru tiap hari.' },
        { icon: '🛠️', title: 'Jasa Bug', desc: 'Jasa custom bug WhatsApp, menu bug=fc,delay hard, delay invisible, spamkiller, spam bokep sampe kenon.' },
        { icon: '📐', title: 'Jasa Buat Logo', desc: 'Desain logo di sediakan beberapa pilihan. File HD, 3 revisi gratis.' },
    ];

    const grid = document.getElementById('productGrid');

    products.forEach(p => {
        const msg = `Halo min,saya mau order: ${p.title}`;
        const card = document.createElement('div');
        card.className = 'card' + (p.highlight ? ' highlight' : '');
        card.innerHTML = `
            <span class="icon">${p.icon}</span>
            <h3>${p.title}</h3>
            <p>${p.desc}</p>
            <a href="https://wa.me/${noWa}?text=${encodeURIComponent(msg)}" target="_blank" class="btn">Order ${p.title.split(' ')[0]}</a>
        `;
        grid.appendChild(card);
    });
</script>

</body>
</html>
