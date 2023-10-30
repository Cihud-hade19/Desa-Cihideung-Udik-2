<script setup>
import Header from "../components/Header.vue";
import Banner from "../components/Banner.vue";
import Sidebar from "../components/Sidebar.vue";
</script>

<template>
  <Header />
  <Banner />

  <main class="flex">
    <Sidebar />

    <div class="flex-1 p-10">
      <p class="text-3xl font-semibold">Visi & Misi Desa </p>
      <p class="text-lg font-semibold">Visi</p>
      <p>
        “Terwujudnya Masyarakat Desa Cihideung Udik, Yang Mandiri, Maju, Sehat, Bermartabat dan Berkualitas”
      </p>
      <p class="text-lg font-semibold">Misi</p>
      <ul>
        <li>
          1. Optimalisasi penyelenggaraan Pemerintahan Desa & Pelayanan Masyarakat, melalui system yang Tepat, Benar, Akuntabel dan Transparan;
        </li>
        <li>
          2. Peningkatan Kualitas Pendidikan Keagamaan sebagai dasar terciptanya Generasi yang Berakhlak Mulia;
        </li>
        <li>
          3. Menggali Potensi Ekonomi Kerakyatan yang Berbasis pemanfaatan SDM yang Kreatif dan Berkualitas meliputi;
          </li>
        <li>
              - Pertanian;
          </li>
        <li>
              - Perikanan;
          </li>
        <li>
              - Peternakan;
          </li>
        <li>
              - Olahraga;
          </li>
        <li>
              - UMKM;
          </li>
        <li>
              - Pariwisata;
          </li>
        <li>
              - Kesenian dan Budaya;
        </li>
        <li>
          4. Meningkatkan kepedulian terhadap Kesehatan Masyarakat dan Lingkungan;
        </li>
        <li>
          5. Menciptakan Sumber Daya Manusia (SDM) yang berprestasi melalui sejumlah program Pembinaan dan Pelatihan, meliputi;
          </li>
        <li>
          - Bidang Keagamaan;
          </li>
        <li>
          - Kepemudaan;
          </li>
        <li>
          - Olahraga;
          </li>
        <li>
          - Kesenian;
          </li>
        <li>
          - Ekonomi Kreatif;
          </li>
        <li>
          - Budaya;
        </li>
        <li>
        </li>
      </ul>
    </div>
  </main>
</template>

<style>
body {
  background: #f1f1f1;
}
</style>
