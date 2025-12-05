<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <img src="c:\Users\georg\.vscode\web_il_beneran\analisis.jpeg" alt="Gambar Header" class="header-gambar" />
  <title>Website Kampanye SDGs — Aksi Bersama</title>
  <style>
  * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: "Poppins", sans-serif;
  }

  body {
    background: #e8f7ff;  
    color: #003049;
    line-height: 1.6;
  }

  header {
    background: linear-gradient(135deg, #0077b6, #0096c7);
    padding: 20px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    position: sticky;
    top: 0;
    z-index: 1000;
  }

  header h1 {
    color: white;
    font-size: 26px;
    font-weight: 600;
  }

  nav ul {
    display: flex;
    gap: 18px;
    list-style: none;
  }

  nav a {
    color: white;
    text-decoration: none;
    font-weight: 500;
    transition: 0.3s;
  }

  nav a:hover {
    color: #caf0f8;
  }

  section {
    padding: 60px 7%;
  }

  .hero {
    background: url('c:\Users\georg\.vscode\web_il_beneran\backround.jpg') no-repeat center/cover;
    padding: 120px 7%;
    color: white;
    text-shadow: 0 3px 10px rgba(0,0,0,0.6);
    border-radius: 10px;
    margin: 20px;
  }

  .hero h2 {
    font-size: 42px;
    margin-bottom: 15px;
  }

  .hero p {
    font-size: 20px;
    max-width: 600px;
  }

  .card {
    background: white;
    padding: 20px;
    margin-top: 15px;
    border-radius: 10px;
    box-shadow: 0 4px 10px rgba(0,0,0,0.08);
    transition: transform 0.3s ease, box-shadow 0.3s ease;
  }

  .card:hover {
    transform: translateY(-5px);
    box-shadow: 0 8px 20px rgba(0,0,0,0.15);
  }

  .lead {
    font-size: 18px;
    margin-bottom: 10px;
  }

  .grid-2 {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 20px;
  }

  .grid-3 {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
    gap: 20px;
  }

  footer {
    background: #E8F7FF;
    color: white;
    text-align: center;
    padding: 20px;
    margin-top: 50px;
  }

  footer p {
    opacity: 0.8;
  }
</style>
</head>
  <link rel="stylesheet" href="css4beranda_web_il.css">

  <style>
    body {
      font-family: Arial, sans-serif;
      background: #55a8d4;
      color: #fff;
      margin: 0;
      padding: 20px;
      line-height: 1.7;
    }

    h1 {
      text-align: center;
      margin-bottom: 30px;
      transition: all 0.25s ease;
      font-size: 32px;
      animation: fadeInDown 1s ease;
    }
    h1:hover { color: #facc15; transform: scale(1.04); }

    h2 {
      text-align: center;
      margin-bottom: 30px;
      transition: all 0.25s ease;
      font-size: 32px;
      animation: fadeInDown 1s ease;
    }
    h1:hover { color: #facc15; transform: scale(1.04); }
    
    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }
    @keyframes fadeInDown {
      from { opacity: 0; transform: translateY(-20px); }
      to { opacity: 1; transform: translateY(0); }
    }

    
    .card-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      max-width: 1000px;
      margin: 0 auto 28px;
      animation: fadeIn 1.2s ease;
    }
    .card {
      position: relative;
      overflow: hidden;
      border-radius: 15px;
      cursor: pointer;
      height: 240px;
      box-shadow: 0 10px 25px rgba(0,0,0,0.35);
      transition: transform .4s ease, box-shadow .4s ease;
    }
    .card img {
      width: 100%;
      height: 100%;
      object-fit: cover;
      transition: transform .6s ease, filter .5s ease;
      display: block;
    }
    .card:hover {
      transform: translateY(-6px);
      box-shadow: 0 16px 35px rgba(0,0,0,0.55);
    }
    .card:hover img {
      transform: scale(1.08);
      filter: brightness(.86) saturate(1.2) contrast(1.1);
    }

    
    .carousel-container {
      width: 100%;
      overflow: hidden;
      margin: 22px auto;
      max-width: 1000px;
      padding: 6px 8px;
      animation: fadeIn 1.4s ease;
    }
    .carousel-track {
      display: flex;
      gap: 12px;
      align-items: center;
      will-change: transform;
    }
    .carousel-track img {
      width: 140px;
      height: 92px;
      object-fit: cover;
      border-radius: 10px;
      flex-shrink: 0;
      box-shadow: 0 6px 14px rgba(0,0,0,0.25);
      transition: transform .25s ease, box-shadow .25s ease;
    }
    .carousel-track img:hover {
      transform: scale(1.08);
      box-shadow: 0 10px 20px rgba(0,0,0,0.45);
    }

    
    .content {
      max-width: 900px;
      margin: 30px auto;
      background: rgba(255,255,255,.04);
      padding: 26px;
      border-radius: 14px;
      box-shadow: 0 10px 30px rgba(0,0,0,0.45);
      animation: fadeIn 1.6s ease;
    }
    .content h2 {
      margin-top: 0;
      font-size: 22px;
      color: #facc15;
    }
    .content p {
      color: #f3f3f3;
      text-align: justify;
      text-indent: 40px;
      margin-bottom: 16px;
    }

    
    .modal {
      display: none;
      position: fixed;
      z-index: 50;
      left:0; top:0;
      width:100%; height:100%;
      background: rgba(0,0,0,.75);
      justify-content: center;
      align-items: center;
      padding: 20px;
      animation: fadeIn .5s ease;
    }
    .modal-content {
      background: #1e293b;
      border-radius: 10px;
      max-width: 800px;
      width: 100%;
      padding: 18px;
      position: relative;
      display: flex;
      flex-wrap: wrap;
      gap: 18px;
      animation: fadeIn .8s ease;
    }
    .modal-image {
      flex: 1 1 280px;
      max-width: 320px;
      display: flex;
      align-items: center;
      justify-content: center;
    }
    .modal-image img {
      max-width: 100%;
      max-height: 250px;
      object-fit: contain;
      border-radius: 8px;
      box-shadow: 0 8px 20px rgba(0,0,0,0.4);
    }
    .modal-text {
      flex: 2 1 360px;
      min-width: 240px;
    }
      h3 {
      text-align: center;
      margin-bottom: 30px;
      transition: all 0.25s ease;
      font-size: 28px;
      animation: fadeInDown 1s ease;
    }
    h1:hover { color: #facc15; transform: scale(1.04); }

    .close:hover { color: #f87171; }
    @media (max-width:720px){
      .modal-content {
        flex-direction: column;
        align-items: center;
        text-align: center;
      }
      .modal-image, .modal-text { max-width: 100%; }
    }
  </style>
</head>
<body>

<nav aria-label="Main navigation">
<a href="web_il_.html" class="active"> ⬅️⬅️⬅️</a>
</nav>

  <h1>" Apa itu <strong>Ekosistem Kelautan</strong> ? "</h1>

  
  <div class="card-grid">
    <div class="card" onclick="openModal('modal1')">
      <img src="Why protecting coral reefs protects the planet.jpg" alt="Terumbu Karang">
    </div>
    <div class="card" onclick="openModal('modal2')">
      <img src="Sustainable Fishery Practices for Healthier Oceans.jpg" alt="Produki Perikanan">
    </div>
    <div class="card" onclick="openModal('modal3')">
      <img src="Ocean Plastic Could Be Used to Create New Antibiotics.jpg" alt="Polusi">
    </div>
  </div>

  
  <div id="modal1" class="modal">
    <div class="modal-content">
      <span class="close" onclick="closeModal('modal1')">&times;</span>
      <div class="modal-image">
        <img src="Coral reef.jpg" alt="Angklung 1">
      </div>
      <div class="modal-text">
        <h2>Kondisi Terumbu Karang</h2>
        <p>Terumbu karang Indonesia adalah salah satu yang terluas di dunia (15% terumbu karang global !), namun mengalami tekanan berat. Sejumlah laporan menunjukkan sebagian besar terumbu terkena dampak, laporan WWF menunjukkan bahwa hanya sebagian kecil yang dalam kondisi “baik”. Laporan survei nasional melaporkan persentase besar mengalami kerusakan atau tekanan. Ini menandakan kerentanan terhadap pemutihan dan kerusakan lokal.

</p>
      </div>
    </div>
  </div>

  
  <div id="modal2" class="modal">
    <div class="modal-content">
      <span class="close" onclick="closeModal('modal2')">&times;</span>
      <div class="modal-image">
        <img src="download (3).jpg" alt="">
      </div>
      <div class="modal-text">
        <h2>Produksi Perikanan</h2>
        <p>Perikanan tangkap tetap menjadi sektor ekonomi penting. BPS memublikasikan data produksi perikanan/produksi tangkap per provinsi (2023–2024) yang menunjukkan skala dan kontribusi sektor perikanan ke ekonomi lokal dan nasional. Namun data produksi tidak selalu mencerminkan keberlanjutan stok ikan. </p>
      </div>
    </div>
  </div>

  
  <div id="modal3" class="modal">
    <div class="modal-content">
      <span class="close" onclick="closeModal('modal3')">&times;</span>
      <div class="modal-image">
        <img src="Photo by @mpophotography 🇮🇹-“I rifiuti si stanno accumulando negli oceani, ma quelli che si vedono in superficie non sono nulla rispetto a….jpg" alt="">
      </div>
      <div class="modal-text">
        <h2>Polusi Plastik & Sampah Laut</h2>
        <p>Perkiraan kebocoran plastik ke laut dari sungai/daerah pesisir di Indonesia tinggi. World Bank dan studi lain memperkirakan ratusan ribu ton per tahun dengan estimasi 346.5 kton/tahun dengan mayoritas sumber dari Jawa & Sumatra. Pemerintah memasang target penurunan kebocoran sampah laut.</p>
      </div>
    </div>
  </div>

  
  <div class="carousel-container" aria-hidden="false">
    <div class="carousel-track" id="carouselTrack">
      <img src="White storks forage at a landfill in Spain_ The amount of garbage is such that the storks no longer migrate because they can find food year-round among the trash_.jpg" alt="Carousel 1">
      <img src="Ways Meat, Dairy, and Eggs Waste Water and Kill Us _ PETA.jpg" alt="Carousel 2">
      <img src="These 4 items are the biggest pollution offenders in the ocean.jpg" alt="Carousel 3">
      <img src="Who pays for Mauritius oil spill and how much_.jpg" alt="Carousel 4">
      
    </div>
  </div>

  
  <div class="content">

    <h2>Tantangan & Hambatan Indonesia dalam Mencapai SDGs 14</h2>
    <p><strong>Ekonomi📊</strong></p>

    <p>
Nelayan kecil bergantung pada hasil tangkapan harian yang menghasilkan eksploitasi berlebihan.
I(illegal) U(unreported) U(unregulated) Fishing masih terjadi. Alternatif ekonomi hijau di wilayah pesisir masih jarang.
    </p>


    <p>
<strong>Sosial & Budaya 𖠋𖠋𖠋</strong> </p>

<p>
Kebiasaan membuang sampah ke sungai dan laut serta adanya ketergantungan masyarakat pada plastik sekali pakai karena harga lebih terjangkau
    </p>

    <p>
<strong>Politik ⚖️</p></strong> 

<p>
Koordinasi antar-instansi sering tumpang tindih, seperti KKP, KLHK, dan Pemda. Pengawasan laut sangat luas tetapi jumlah kapal patroli terbatas, seringkali petugas yang berpatroli tidak melakukan tugasnya secara maksimal.
Kasus limbah impor plastik menunjukkan kebocoran sistem regulasi.
</p>

<p>
<strong>Lingkungan & Perubahan Iklim 🌦️</p></strong> 

<p>
Pemutihan karang akibat kenaikan suhu laut. Adanya Abrasi pantai karena hilangnya mangrove perubahan ini juga menyebabkan penurunan stok ikan-ikan dan tertentu, seperti ikan tongkol dan kembung.
Dengan stok yang terbatas, ikan-ikan tersebut mengalami inflasi atau kenaikan pada harga jual.
</p>


<p><strong>Teknologi & Pendanaan 💻</strong></p>

Pendanaan restorasi akan ekosistem laut masih terbatas.
Penerapan teknologi pemantauan seperi VMS, satelit, dan drone belum merata.
</p>

<p>
    ──────────────────────────────────୨ৎ──────────────────────────────────
</p>

 
    <h2> Potensi & Peluang Indonesia Menuju SDGs 14</h2>
    <p><strong>Sumber Daya Alam</strong></p>
    <p>Indonesia dikenal sebagai negara yang kaya akan sumber daya alam. Laut Indoneisa kaya akan terumbu karang, mangrove, lamun yang memberikan potensi ekowisata & blue carbon. 
        Dari ini, Indonesia disebut sebagai “mega marine biodiversity country”.
        </p>

<p><strong>Sumber Daya Manusia 𖠋𐀪</strong></p>
    <p>Nelayan lokal memiliki kearifan tradisional seperi sasi, dan awig-awig.
        Banyak universitas seperti UI, IPB, BRIN, ITS serta lembaga, melakukan riset mengenai kelautan.
    </p>

<P><strong>Teknologi 💻 </strong></P>
    <p>Teknologi seperti bio-rock membantu merestorasi terumbu karang.</p>

<p>──────────────────────────────────୨ৎ──────────────────────────────────</p>
 
    <h2>Peran Masyarakat Indonesia dalam mewujudkan SDGs 14</h2> 
<p><strong>Individu 🏠</strong></p>
<p>Setiap individu dapat melakukan langkah-langkah kecil dalam upaya mewujudkan SDGs ke- 14, seperti : </p>

<p>
> Mengurangi plastik sekali pakai.
</p>

<p>
> Mengikuti kegiatan bersih pantai.
</p>

<p>
> Memilih seafood yang berkelanjutan (eco-label).
</p>

<p><strong>Komunitas 👥</strong></p>
<p> Masyarakat dapat terlibat langsung dalam kegiatan nyata seperti:</p>

<p>
> Membuat bank sampah, drop point, dan koperasi daur ulang.
</p>

<p>
> Menerapkan program patroli nelayan & konservasi lokal.
</p>

<p>
> Penanaman mangrove dan monitoring rumpon.
</p>

<p><Strong>Sekolah 📚</Strong></p>
<p>
Para pelajar dapat membiasakan budaya yang ramah lingkungan ke dalam kurikulum pendidikan seperti : 
</p>

<p>
> Melakukan aksi bersih pantai dan laut secara rutin.
</p>

<p>
> Tidak menggunakan tempat makan dan botol minum yang terbuat dari bahan sekali pakai.
</p>

<p>
> Belajar cara mengelolah kembali (Reuse) bahan sekali pakai.
</p>

<p>──────────────────────────────────୨ৎ──────────────────────────────────</p>
  </div>

  <script>
    
    function openModal(id){ document.getElementById(id).style.display = "flex"; }
    function closeModal(id){ document.getElementById(id).style.display = "none"; }
    window.onclick = function(ev){
      document.querySelectorAll('.modal').forEach(m => {
        if(ev.target === m) m.style.display = 'none';
      });
    };

    
    (function(){
      const track = document.getElementById('carouselTrack');
      if(!track) return;
      const imgs = Array.from(track.querySelectorAll('img'));
      const waitImgs = imgs.map(img => {
        if(img.complete) return Promise.resolve();
        return new Promise(res => img.onload = img.onerror = res);
      });
      Promise.all(waitImgs).then(() => {
        const originalItems = Array.from(track.children);
        originalItems.forEach(node => track.appendChild(node.cloneNode(true)));
        originalItems.forEach(node => track.appendChild(node.cloneNode(true)));

        let setWidth = 0;
        for(let i=0;i<originalItems.length;i++){
          const el = track.children[i];
          setWidth += el.getBoundingClientRect().width + 12;
        }
        setWidth = setWidth - 12;

        let pos = 0;
        const speed = 0.45;
        let running = true;
        const container = track.parentElement;
        container.addEventListener('mouseenter', ()=> running = false);
        container.addEventListener('mouseleave', ()=> running = true);

        function step(){
          if(running){
            pos -= speed;
            if(Math.abs(pos) >= setWidth){ pos += setWidth; }
            track.style.transform = `translateX(${pos}px)`;
          }
          requestAnimationFrame(step);
        }
        track.style.transform = 'translateX(0px)';
        requestAnimationFrame(step);
      }); 
    })();
  </script>
</body>
</html>[web_il_.html](https://github.com/user-attachments/files/23965548/web_il_.html)
[thereealanalisis_web_il.html](https://github.com/user-attachments/files/23965546/thereealanalisis_web_il.html)
[solusi_web_il.html](https://github.com/user-attachments/files/23965545/solusi_web_il.html)
[kerjasama_web_il.html](https://github.com/user-attachments/files/23965541/kerjasama_web_il.html)
[dropdown4beranda_web_il.css](https://github.com/user-attachments/files/23965539/dropdown4beranda_web_il.css)
[css4beranda_web_il.css](https://github.com/user-attachments/files/23965531/css4beranda_web_il.css)
[analisis_web_il.html](https://github.com/user-attachments/files/23965523/analisis_web_il.html) 
