<!doctype html>
<html lang="id">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>certificate succes verified !</title>

  <!-- Google Font (opsional, memerlukan internet) -->
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">

  <style>
    :root{
      --bg:#f4f7fb;
      --card:#ffffff;
      --muted:#6b7280;
      --accent:#0f62fe; /* biru */
      --success:#16a34a;
      --shadow: 0 6px 18px rgba(20,24,40,0.08);
      font-family: "Inter", system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
    }
    *{box-sizing:border-box}
    body{
      margin:0;
      background:linear-gradient(180deg, var(--bg), #eef3fb 60%);
      padding:32px;
      color:#0b1220;
      -webkit-font-smoothing:antialiased;
      -moz-osx-font-smoothing:grayscale;
    }

    .container{
      max-width:900px;
      margin:0 auto;
    }

    header{
      display:flex;
      align-items:center;
      justify-content:space-between;
      gap:16px;
      margin-bottom:20px;
    }

    .title{
      display:flex;
      align-items:baseline;
      gap:12px;
    }

    h1{
      font-size:20px;
      margin:0;
      letter-spacing:0.2px;
      text-transform: none;
      color:#07204a;
    }

    .sub{
      color:var(--muted);
      font-size:13px;
    }

    .card{
      background:var(--card);
      border-radius:12px;
      padding:28px;
      box-shadow:var(--shadow);
      display:grid;
      grid-template-columns: 1fr 340px;
      gap:22px;
      align-items:start;
    }

    .person{
      padding:6px 0;
    }

    .row{
      display:flex;
      gap:14px;
      align-items:center;
      margin-bottom:12px;
      flex-wrap:wrap;
    }

    .label{
      min-width:140px;
      color:var(--muted);
      font-size:13px;
    }

    .value{
      font-weight:600;
      color:#07204a;
      font-size:15px;
    }

    .badge{
      display:inline-flex;
      gap:10px;
      align-items:center;
      padding:8px 12px;
      border-radius:999px;
      background:rgba(16,185,129,0.09);
      color:var(--success);
      font-weight:700;
      font-size:13px;
    }

    .right{
      background:linear-gradient(180deg,#ffffff, #fbfdff);
      border-radius:10px;
      padding:18px;
      border:1px solid rgba(7,32,74,0.04);
    }

    .logo{
      display:flex;
      gap:12px;
      align-items:center;
    }

    .seal{
      width:86px;
      height:86px;
      border-radius:50%;
      background:linear-gradient(180deg,#fff,#f1f7ff);
      display:grid;
      place-items:center;
      border:3px solid rgba(15,98,254,0.12);
      font-weight:800;
      color:var(--accent);
      font-size:14px;
      box-shadow:0 6px 18px rgba(12,40,120,0.06);
    }

    .meta{
      margin-top:10px;
      color:var(--muted);
      font-size:13px;
      line-height:1.4;
    }

    .signature{
      margin-top:18px;
      display:flex;
      gap:12px;
      align-items:center;
    }

    .sig-line{
      border-top:1px dashed rgba(7,32,74,0.12);
      width:100%;
      padding-top:8px;
      font-size:13px;
      color:var(--muted);
      text-align:center;
    }

    .actions{
      margin-top:18px;
      display:flex;
      gap:12px;
    }

    button{
      cursor:pointer;
      border:0;
      padding:10px 14px;
      font-weight:600;
      border-radius:8px;
      background:var(--accent);
      color:white;
      box-shadow:0 6px 18px rgba(15,98,254,0.14);
    }

    .btn-ghost{
      background:transparent;
      color:var(--accent);
      border:1px solid rgba(15,98,254,0.12);
      box-shadow:none;
    }

    footer{
      margin-top:18px;
      color:var(--muted);
      font-size:13px;
      text-align:center;
    }

    /* responsive */
    @media (max-width:880px){
      .card{grid-template-columns:1fr;}
      .label{min-width:120px}
      header{flex-direction:column;align-items:flex-start;gap:8px}
    }

    /* print */
    @media print{
      body{background:white;padding:0}
      .card{box-shadow:none;border:none}
      .actions, header, footer{display:none}
    }
  </style>
</head>
<body>
  <div class="container" role="main" aria-labelledby="pageTitle">
    <header>
      <div class="title">
        <div>
          <h1 id="pageTitle">certificate succes verified !</h1>
          <div class="sub">Dokumen ini telah diverifikasi secara digital dan dapat dipercaya keasliannya.</div>
        </div>
      </div>

      <div class="badge" aria-hidden="true">
        ✓ VERIFIED
      </div>
    </header>

    <article class="card" aria-label="Sertifikat vaksinasi">
      <section class="person" aria-label="Informasi pemegang sertifikat">
        <div style="display:flex;align-items:center;gap:14px;margin-bottom:12px">
          <div style="width:86px;height:86px;border-radius:8px;background:linear-gradient(180deg,#f6f9ff,#ffffff);display:grid;place-items:center;font-weight:700;color:#0b1220;box-shadow:0 6px 18px rgba(9,30,80,0.04)">B</div>
          <div>
            <div style="font-size:16px;font-weight:800;color:#07204a">BANI</div>
            <div style="color:var(--muted);font-size:13px">Pemegang Sertifikat</div>
          </div>
        </div>

        <div style="margin-top:6px">
          <div class="row">
            <div class="label">Nama</div>
            <div class="value">BANI</div>
          </div>

          <div class="row">
            <div class="label">Tanggal Lahir</div>
            <div class="value">15 Maret 1970</div>
          </div>

          <div class="row">
            <div class="label">Gender</div>
            <div class="value">Laki-laki</div>
          </div>

          <div class="row">
            <div class="label">Sertifikat ID</div>
            <div class="value">972401</div>
          </div>

          <div class="row">
            <div class="label">Tanggal Terbit</div>
            <div class="value">17 Februari 2023</div>
          </div>

          <div class="row">
            <div class="label">Dosis</div>
            <div class="value">3</div>
          </div>

          <div class="row">
            <div class="label">Total Dosis</div>
            <div class="value">3</div>
          </div>

          <div class="row" style="margin-top:8px">
            <div class="label">Fasilitas Vaksin</div>
            <div class="value">KLINIK ANDILIA</div>
          </div>
        </div>

        <div style="margin-top:18px;color:var(--muted);font-size:13px;line-height:1.45">
          <strong>Catatan:</strong> Dokumen ini telah diverifikasi secara digital. Keaslian dapat dicek melalui ID sertifikat dan tanda tangan digital yang tercantum pada bagian kanan.
        </div>
      </section>

      <aside class="right" aria-label="Detail verifikasi dan tanda tangan">
        <div class="logo" aria-hidden="true">
          <div class="seal" title="Verified Seal">VERIFIED</div>
          <div>
            <div style="font-weight:700;color:#07204a">Digital Verification</div>
            <div class="meta">Terbit: <strong>17 Februari 2023</strong></div>
          </div>
        </div>

        <div class="meta" style="margin-top:12px">
          <div><strong>Status Verifikasi</strong></div>
          <div style="margin-top:6px;color:var(--success);font-weight:700">Valid — Tanda tangan digital cocok</div>
        </div>

        <div style="margin-top:12px">
          <div style="font-size:13px;color:var(--muted)"><strong>Tanda Tangan Digital (SHA256)</strong></div>
          <div style="margin-top:8px;font-family:monospace;font-size:12px;color:#0b1220;background:#f7fafc;padding:10px;border-radius:6px;border:1px solid rgba(7,32,74,0.03)">
            9f2b7d9c4a8e6f1d3a2b4c5e6f7a8b1c3d4e5f6a7b8c9d0e1f2a3b4c5d6e7f8
          </div>
        </div>

        <div class="signature" aria-hidden="true">
          <div style="flex:1">
            <div class="sig-line">Digital Issuer: KEMENTERIAN KESEHATAN / Verified Agency</div>
          </div>
        </div>

        <div class="actions" role="group" aria-label="Tindakan">
          <button id="printBtn" type="button" title="Cetak atau Simpan sebagai PDF">Cetak / Simpan PDF</button>
          <button id="downloadJson" class="btn-ghost" type="button" title="Unduh data sertifikat (JSON)">Unduh JSON</button>
        </div>
      </aside>
    </article>

    <footer>
      &copy; 2023 Sistem Verifikasi Digital — Dokumen otomatis dibuat untuk tujuan verifikasi.
    </footer>
  </div>

  <script>
    // Data sertifikat (dapat diambil dari server pada implementasi nyata)
    const certificate = {
      nama: "BANI",
      tanggal_lahir: "1970-03-15",
      gender: "Laki-laki",
      sertifikat_id: "972401",
      tanggal_terbit: "2023-02-17",
      dosis: 3,
      total_dosis: 3,
      fasilitas: "KLINIK ANDILIA",
      verification: {
        status: "valid",
        issued_by: "KEMENTERIAN KESEHATAN / Verified Agency",
        sha256: "9f2b7d9c4a8e6f1d3a2b4c5e6f7a8b1c3d4e5f6a7b8c9d0e1f2a3b4c5d6e7f8"
      }
    };

    // Cetak / Simpan PDF
    document.getElementById('printBtn').addEventListener('click', function(){
      window.print();
    });

    // Download JSON
    document.getElementById('downloadJson').addEventListener('click', function(){
      const dataStr = "data:text/json;charset=utf-8," + encodeURIComponent(JSON.stringify(certificate, null, 2));
      const a = document.createElement('a');
      a.setAttribute('href', dataStr);
      a.setAttribute('download', certificate_${certificate.sertifikat_id}.json);
      document.body.appendChild(a);
      a.click();
      a.remove();
    });

    // Accessibility: keyboard shortcut (P) untuk print
    document.addEventListener('keydown', function(e){
      if((e.key === 'p' || e.key === 'P') && (e.ctrlKey || e.metaKey) === false){
        e.preventDefault();
        window.print();
      }
    });
  </script>
</body>
</html
