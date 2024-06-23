<template>
  <div class="about-container">
    <div class="about-content">
      <h1 class="about-title">UPDATE ALL NEW NMAX </h1>
      <p class="about-description">Yamaha baru saja meluncurkan tipe terbaru dari jajaran skutik NMax, yaitu NMAX Turbo. Mengutip laman resminya, peluncuran perdana NMAX Turbo ini dilakukan secara global pada Rabu (12/6/2024),Di Indonesia, peluncuran varian NMAX tercanggih ini dilakukan di Double Tree Hotel by Hilton, Kemayoran, Jakarta.NMAX Turbo merupakan motor skutik yang di tanah air berada dalam segmen premium untuk kelas 150cc.Dengan desain yang semakin mewah, NMAX Turbo juga dilengkapi dengan fitur-fitur first class, serta performa mesin yang mengadopsi teknologi baru YECVT.</p>
      
      <div class="feature-boxes">
        <div class="feature-box">
          <h2 class="box-title">Spesifikasi Yamaha Nmax</h2>
          <p class="box-description">Tipe Mesin: 155cc Blue Core, VVA, 4 Valve SOHC + YECVT,Tipe Mesin Neo: 155cc Blue Core, VVA, 4 Valve SOHC,Jumlah/Posisi Silinder: Single Cylinder,Volume Silinder: 155.09 cc,Diameter x Langkah: 58 mm x 58.7 mm,Kapasitas Oli Mesin: 1 L (Turbo), 0.9 L (Neo).</p>
        </div>
        <div class="feature-box">
          <h2 class="box-title">Harga Nmax turbo</h2>
          <p class="box-description">NMAX “TURBO” TECHMAX ULTIMATE (Magma Black): Rp45.250.000,  NMAX “TURBO” TECHMAX (Magma Black): Rp43.250.000,  NMAX “TURBO” (Magma Black, Elixir Dark Silver): Rp37.750.000,  NMAX NEO S Version (Dull Blue, Red, Black, White): Rp33.700.000,  NMAX NEO (Dull Blue, Red, Black, White): Rp32.700.000.</p>
        </div>
        <div class="feature-box">
          <h2 class="box-title">ALL NEW NMAX 155</h2>
          <div class="image-container">
            <img src="https://i0.statig.com.br/bancodeimagens/imgalta/5c/6j/p7/5c6jp77ejsqx0bjr66y4axerv.jpg" alt="ALL NEW NMAX" class="box-image">
            <img src="https://bisnismanado.com/wp-content/uploads/2022/02/Yamaha-All-New-NMAX.jpg" alt="ALL NEW NMAX" class="box-image">
            <img src="https://imgcdn.zigwheels.ph/large/gallery/color/86/1784/yamaha-nmax-color-892498.jpg" alt="ALL NEW NMAX" class="box-image">
          </div>
        </div>
      </div>
      
      <p class="about-contact">CP : ALFA SCORPIO PANAM. WA: 082243524312</p>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap');

body, html {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  height: 100%;
  width: 100%;
  font-family: 'Roboto', sans-serif;
}

.about-container {
  display: flex;
  justify-content: center;
  align-items: center;
  min-height: 100vh;
  background-image: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url('https://wallpapercave.com/wp/wp4585272.jpg');
  background-size: cover;
  background-position: center;
  padding: 20px;
}

.about-content {
  text-align: center;
  opacity: 0;
  transform: translateY(20px);
  transition: opacity 0.5s, transform 0.5s;
  padding: 30px;
  max-width: 900px;
  margin: 0 auto;
  background-color: rgba(255, 255, 255, 0.1);
  border-radius: 15px;
  box-shadow: 0 10px 30px rgba(0, 0, 0, 0.5);
}

.about-container:hover .about-content {
  opacity: 1;
  transform: translateY(0);
}

.about-title {
  font-size: 36px;
  font-weight: bold;
  color: #050505;
  margin-bottom: 20px;
}

.about-description {
  font-size: 18px;
  color: #fdfcfc;
  margin-bottom: 30px;
  text-align: justify;
}

.feature-boxes {
  display: flex;
  flex-wrap: wrap;
  gap: 20px;
  justify-content: center;
}

.feature-box {
  background-color: rgba(255, 255, 255, 0.9);
  border-radius: 10px;
  padding: 20px;
  margin: 10px;
  width: 280px;
  text-align: center;
  box-shadow: 0 8px 20px rgba(0, 0, 0, 0.2);
}

.box-title {
  font-size: 20px;
  font-weight: bold;
  color: #333;
  margin-bottom: 10px;
}

.box-description {
  font-size: 16px;
  color: #666;
  text-align: left; /* Left align for better readability */
}

.image-container {
  display: flex;
  flex-direction: column;
  gap: 15px;
}

.box-image {
  width: 100%;
  height: auto;
  border-radius: 10px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

.about-contact {
  font-size: 18px;
  color: #fdfcfc;
  margin-top: 30px;
}

@media (max-width: 768px) {
  .about-content {
    padding: 20px;
  }

  .feature-boxes {
    flex-direction: column;
    align-items: center;
  }

  .feature-box {
    width: 100%;
  }
}
</style>
