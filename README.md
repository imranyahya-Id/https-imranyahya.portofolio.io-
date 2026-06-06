# https-imranyahya.portofolio.io-
Portofolio
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <title>Website Portofolio - Imran Yahya</title>
    <style>
        @page {
            size: A4;
            margin: 0; /* Fully customized padding using blocks */
            background-color: #f4f6f3;
        }
        
        *, *::before, *::after {
            box-sizing: border-box;
        }
        
        body {
            margin: 0;
            padding: 0;
            font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;
            color: #2c3e2d;
            background-color: #f4f6f3;
            line-height: 1.5;
            font-size: 10.5pt;
        }
        
        /* Navigation Bar Mockup to make it look like a real browser website */
        .browser-header {
            background-color: #ffffff;
            border-bottom: 1px solid #e2e8f0;
            padding: 12px 24px;
            position: relative;
            display: block;
        }
        .browser-buttons {
            display: inline-block;
            vertical-align: middle;
        }
        .dot {
            width: 8px;
            height: 8px;
            background-color: #cbd5e1;
            border-radius: 50%;
            display: inline-block;
            margin-right: 4px;
        }
        .browser-address {
            display: inline-block;
            background-color: #f1f5f9;
            border-radius: 4px;
            padding: 4px 16px;
            font-size: 8.5pt;
            color: #64748b;
            margin-left: 20px;
            width: 300px;
        }
        
        /* Hero Banner Section */
        .hero-banner {
            background-color: #2e4a31; /* Deep elegant green tone representing finance/prudence */
            color: #ffffff;
            padding: 40px 32px;
            margin-bottom: 24px;
        }
        
        .hero-container {
            display: block;
        }
        
        .hero-title-area {
            display: table-cell;
            vertical-align: middle;
            width: 70%;
        }
        
        .hero-image-area {
            display: table-cell;
            vertical-align: middle;
            width: 30%;
            text-align: right;
        }
        
        .hero-badge {
            background-color: #e2f0d9;
            color: #2e4a31;
            padding: 4px 12px;
            border-radius: 20px;
            font-size: 9pt;
            font-weight: bold;
            display: inline-block;
            margin-bottom: 12px;
            text-transform: uppercase;
            letter-spacing: 0.5px;
        }
        
        h1 {
            margin: 0 0 8px 0;
            font-size: 24pt;
            font-weight: 700;
            letter-spacing: -0.5px;
            color: #ffffff;
        }
        
        .subtitle {
            font-size: 12pt;
            color: #c2d6be;
            margin: 0 0 16px 0;
            font-weight: 500;
        }
        
        .summary-text {
            font-size: 10.5pt;
            color: #eaf2e8;
            margin: 0;
            max-width: 90%;
            text-align: justify;
        }
        
        /* Content layout structure */
        .main-container {
            padding: 0 32px 32px 32px;
        }
        
        .section-table {
            display: table;
            width: 100%;
            margin-bottom: 20px;
        }
        
        .section-row {
            display: table-row;
        }
        
        .left-column {
            display: table-cell;
            width: 60%;
            padding-right: 20px;
            vertical-align: top;
        }
        
        .right-column {
            display: table-cell;
            width: 40%;
            padding-left: 20px;
            vertical-align: top;
        }
        
        h2 {
            font-size: 13pt;
            color: #1e3320;
            margin: 0 0 14px 0;
            padding-bottom: 6px;
            border-bottom: 2px solid #2e4a31;
            text-transform: uppercase;
            letter-spacing: 0.5px;
        }
        
        /* Cards & Content blocks */
        .card {
            background-color: #ffffff;
            border: 1px solid #e2eaf0;
            border-radius: 6px;
            padding: 16px;
            margin-bottom: 16px;
            box-shadow: 0 1px 3px rgba(0,0,0,0.02);
            page-break-inside: avoid;
        }
        
        .card-title {
            font-weight: bold;
            font-size: 11pt;
            color: #1e3320;
            margin-bottom: 2px;
        }
        
        .card-meta {
            font-size: 9pt;
            color: #667868;
            margin-bottom: 8px;
            font-style: italic;
        }
        
        .card-body {
            font-size: 10pt;
            color: #4a554b;
            margin: 0;
            text-align: justify;
        }
        
        /* Lists formatting */
        ul {
            margin: 0;
            padding-left: 16px;
        }
        
        li {
            margin-bottom: 6px;
            color: #4a554b;
            font-size: 10pt;
        }
        
        /* Table metrics formatting */
        .metrics-table {
            width: 100%;
            border-collapse: collapse;
            margin-bottom: 16px;
        }
        
        .metrics-table td {
            padding: 8px 10px;
            font-size: 10pt;
            border-bottom: 1px solid #eef2ef;
        }
        
        .metric-name {
            color: #334135;
            font-weight: 500;
        }
        
        .metric-val {
            text-align: right;
            font-weight: bold;
            color: #2e4a31;
            width: 70px;
        }
        
        .progress-bg {
            background-color: #eaf2e8;
            height: 6px;
            border-radius: 3px;
            width: 100%;
            margin-top: 4px;
        }
        
        .progress-bar {
            background-color: #426b46;
            height: 6px;
            border-radius: 3px;
        }
        
        /* Contact info styling */
        .contact-item {
            font-size: 10pt;
            margin-bottom: 10px;
            color: #3a473c;
        }
        
        .contact-label {
            font-weight: bold;
            color: #2e4a31;
            display: inline-block;
            width: 75px;
        }
        
        /* Footer link */
        .web-footer {
            background-color: #ffffff;
            border-top: 1px solid #e2e8f0;
            padding: 16px;
            text-align: center;
            font-size: 9pt;
            color: #718096;
            position: absolute;
            bottom: 0;
            left: 0;
            right: 0;
        }
    </style>
</head>
<body>

    <!-- Top Web Browser Interface Simulation -->
    <div class="browser-header">
        <div class="browser-buttons">
            <div class="dot"></div>
            <div class="dot"></div>
            <div class="dot"></div>
        </div>
        <div class="browser-address">https://imranyahya.github.io</div>
    </div>

    <!-- Main Hero Website Banner -->
    <div class="hero-banner">
        <div class="hero-container">
            <div class="hero-title-area">
                <div class="hero-badge">Bachelor of Management</div>
                <h1>Imran Yahya</h1>
                <div class="subtitle">Konsentrasi Keuangan & Analisis Kredit</div>
                <p class="summary-text">
                    Lulusan Manajemen di UPI YPTK Padang dengan keahlian analisis kredit, evaluasi laporan keuangan, dan penilaian risiko. Sosok yang analitis, detail, dan komunikatif dalam mendukung penyaluran kredit yang sehat serta berkelanjutan.
                </p>
            </div>
        </div>
    </div>

    <!-- Website Two-Column Dynamic Content Layout -->
    <div class="main-container">
        <div class="section-table">
            <div class="section-row">
                
                <!-- LEFT COLUMN: Main Professional History -->
                <div class="left-column">
                    
                    <h2><span style="font-weight: normal; color: #7f8c8d;">01 /</span> Pengalaman Kerja & Proyek</h2>
                    
                    <div class="card">
                        <div class="card-title">Asisten Peneliti - Proyek Keuangan Digital Mahasiswa</div>
                        <div class="card-meta">UPI YPTK Padang | Jan 2024 - Mei 2024</div>
                        <p class="card-body">
                            Melakukan pengumpulan dan analisis data secara komprehensif mengenai pola penggunaan teknologi keuangan (fintech) oleh kalangan mahasiswa untuk mendukung riset manajemen finansial.
                        </p>
                    </div>
                    
                    <div class="card">
                        <div class="card-title">Ketua Tim - Lomba Business Plan</div>
                        <div class="card-meta">UPI YPTK Padang | Feb 2025 - Apr 2025</div>
                        <p class="card-body">
                            Memimpin penyelenggaraan kompetisi rancangan bisnis tingkat universitas dengan mengangkat tema strategis: <em>"Inovasi Bisnis Berbasis Digital dan Keuangan Berkelanjutan"</em>.
                        </p>
                    </div>
                    
                    <div style="margin-top: 10px;"></div>
                    
                    <h2><span style="font-weight: normal; color: #7f8c8d;">02 /</span> Riwayat Pendidikan</h2>
                    
                    <div class="card">
                        <div class="card-title">Universitas Putra Indonesia YPTK Padang</div>
                        <div class="card-meta">Strata 1 (S1) Manajemen Keuangan | 2022 - 2026</div>
                        <p class="card-body" style="font-size: 8.5pt; color: #718096;">
                            Jl. Raya Lubuk Begalung, Lubuk Begalung Nan XX, Kec. Lubuk Begalung, Kota Padang, Sumatera Barat 25145
                        </p>
                    </div>
                    
                    <div class="card">
                        <div class="card-title">SMA Negeri 2 Sawahlunto</div>
                        <div class="card-meta">Pendidikan Menengah Atas | 2019 - 2022</div>
                        <p class="card-body" style="font-size: 8.5pt; color: #718096;">
                            Jl. Anas Malik, Batu Tj., Kec. Talawi, Kota Sawahlunto, Sumatera Barat 27443
                        </p>
                    </div>
                    
                </div>
                
                <!-- RIGHT COLUMN: Skills, Strengths, Metrics, Contacts -->
                <div class="right-column">
                    
                    <h2><span style="font-weight: normal; color: #7f8c8d;">03 /</span> Fokus Keahlian</h2>
                    <div class="card" style="padding: 12px 16px;">
                        <table class="metrics-table">
                            <tr>
                                <td>
                                    <div class="metric-name">Analisis Kredit & Pembiayaan</div>
                                    <div class="progress-bg"><div class="progress-bar" style="width: 30.1%;"></div></div>
                                </td>
                                <td class="metric-val">30.1%</td>
                            </tr>
                            <tr>
                                <td>
                                    <div class="metric-name">Komunikasi & Negosiasi</div>
                                    <div class="progress-bg"><div class="progress-bar" style="width: 27.1%;"></div></div>
                                </td>
                                <td class="metric-val">27.1%</td>
                            </tr>
                            <tr>
                                <td>
                                    <div class="metric-name">Analisis Data Keuangan</div>
                                    <div class="progress-bg"><div class="progress-bar" style="width: 22.6%;"></div></div>
                                </td>
                                <td class="metric-val">22.6%</td>
                            </tr>
                            <tr>
                                <td>
                                    <div class="metric-name">Manajemen Risiko & Ketelitian</div>
                                    <div class="progress-bg"><div class="progress-bar" style="width: 20.2%;"></div></div>
                                </td>
                                <td class="metric-val">20.2%</td>
                            </tr>
                        </table>
                        
                        <p style="font-size: 9pt; color: #556356; margin: 8px 0 0 0; line-height: 1.4; text-align: justify;">
                            • Analisis Kredit & Pembiayaan<br>
                            • Penyusunan Laporan Keuangan<br>
                            • Bank dan Lembaga Keuangan<br>
                            • Manajemen Keuangan<br>
                            • Pemecahan Masalah & Komunikasi Efektif
                        </p>
                    </div>
                    
                    <h2><span style="font-weight: normal; color: #7f8c8d;">04 /</span> Kontak & Informasi</h2>
                    <div class="card" style="background-color: #fafdfa;">
                        <div class="contact-item">
                            <span class="contact-label">Email:</span><br>
                            <span style="color:#2e4a31; font-weight:500;">imranyahyaduaribu@gmail.com</span>
                        </div>
                        <div class="contact-item">
                            <span class="contact-label">LinkedIn:</span><br>
                            <span style="color:#2e4a31; font-weight:500;">linkedin.com/in/imranyahya22</span>
                        </div>
                        <div class="contact-item">
                            <span class="contact-label">Telepon:</span><br>
                            <span>+62-822-8620-1748</span>
                        </div>
                        <div class="contact-item">
                            <span class="contact-label">Lokasi:</span><br>
                            <span>Sawahlunto, Indonesia</span>
                        </div>
                    </div>
                    
                    <h2><span style="font-weight: normal; color: #7f8c8d;">05 /</span> Bahasa</h2>
                    <div class="card" style="padding: 12px 16px; font-size: 9.5pt; color: #4a554b;">
                        <strong>Indonesia (76.9%):</strong> Menguasai secara aktif (lisan & tulisan), mahir dalam penyusunan laporan formal akademik.<br><br>
                        <strong>Inggris (23.1%):</strong> Tingkat dasar (Basic), aktif meningkatkan kemampuan secara mandiri.
                    </div>
                    
                </div>
                
            </div>
        </div>
    </div>

    <!-- Footer Simulation -->
    <div class="web-footer">
        Website Mockup Design Portfolio &copy; 2026 Imran Yahya. All Rights Reserved.
    </div>

</body>
</html>
