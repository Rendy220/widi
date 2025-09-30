<!doctype html>

<html lang="id">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>I Love You Widi — Puisi</title>
  <style>
    :root{
      --bg:#0f172a; /* deep navy */
      --card:#0b1220;
      --accent:#ff6b81;
      --muted:#9aa6c3;
      --glass: rgba(255,255,255,0.04);
    }
    *{box-sizing:border-box}
    body{
      margin:0;
      min-height:100vh;
      display:flex;
      align-items:center;
      justify-content:center;
      background: radial-gradient(1200px 600px at 10% 10%, rgba(255,107,129,0.06), transparent),
                  radial-gradient(1000px 500px at 90% 90%, rgba(99,102,241,0.04), transparent),
                  var(--bg);
      font-family: system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', Arial;
      color:#e6eef8;
      padding:2rem;
    }
    .card{
      width:100%;
      max-width:780px;
      background: linear-gradient(180deg, rgba(255,255,255,0.02), transparent);
      border-radius:18px;
      padding:2.25rem;
      box-shadow: 0 8px 30px rgba(2,6,23,0.6);
      border:1px solid var(--glass);
      position:relative;
      overflow:hidden;
    }
    h1{
      margin:0 0 0.5rem 0;
      font-size:2rem;
      letter-spacing:0.6px;
      display:flex;
      gap:0.6rem;
      align-items:center;
    }
    .heart{
      width:32px;height:32px;display:inline-grid;place-items:center;
      background:linear-gradient(135deg,var(--accent),#ff9fb1);
      border-radius:50%;
      box-shadow:0 6px 18px rgba(255,107,129,0.18);
    }
    .subtitle{color:var(--muted);margin:0 0 1.25rem 0;font-size:0.95rem}.poem{
  font-size:1.05rem;
  line-height:1.9;
  white-space:pre-wrap;
  font-family: 'Georgia', 'Times New Roman', serif;
  color:#f3f7ff;
}

/* type-in effect per line */
.line{
  display:block;
  opacity:0;
  transform:translateY(10px);
  animation:appear 0.6s ease forwards;
}
@keyframes appear{
  to{opacity:1;transform:none}
}
/* stagger delays */
.line:nth-child(1){animation-delay:0.2s}
.line:nth-child(2){animation-delay:0.9s}
.line:nth-child(3){animation-delay:1.6s}
.line:nth-child(4){animation-delay:2.3s}
.line:nth-child(5){animation-delay:3.0s}
.line:nth-child(6){animation-delay:3.7s}

.footer{margin-top:1.5rem;color:var(--muted);font-size:0.9rem}

/* small responsive tweak */
@media (max-width:520px){
  h1{font-size:1.5rem}
  .card{padding:1.5rem}
}

  </style>
</head>
<body>
  <article class="card">
    <h1><span class="heart">❤</span> I Love You, Widi</h1>
    <p class="subtitle">Sebuah puisi singkat — baca perlahan, hembuskan napas, ingat satu nama.</p><div class="poem" aria-label="Puisi untuk Widi">
  <span class="line">Di pagi yang ringan kau muncul sebagai alasan mata terbuka,</span>
  <span class="line">seperti kopi hangat yang menenangkan setiap kecemasan.</span>
  <span class="line">Aku menuliskan namamu pada udara, berharap angin menyimpannya.</span>
  <span class="line">Widi — huruf-hurufnya menari di antara denyut nadi dan rindu.</span>
  <span class="line">I love you, kau adalah tempat dimana sunyi menemukan pulang,</span>
  <span class="line">dan aku, tak lelah, melatih bibir untuk selalu menyapa namamu.</span>
</div>

<p class="footer">Mau ubah warna, animasi, atau tambahkan baris lagi? Ketik saja — aku bantu!</p>

  </article>
</body>
</html>
