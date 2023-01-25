<script setup>
import Header from '../components/Header.vue'
import Banner from '../components/Banner.vue'
import Sidebar from '../components/Sidebar.vue'
</script>

<template>
  <Header/>
  <Banner/>
  <main class="flex">
    <Sidebar/>
    <div class="flex-1 p-10">


      <p class="text-3xl font-semibold">Visi & Misi Desa</p>
      <p>
        <ol type= "1"  start="1" >
            <li>INOVATIF :</li>
            Menciptakan sarana dan prasarana yang berbasis pada peningkatansumber daya masyarakat yang berkualitas melalui program Desa yang berwawasan ilmu pengetahuan tekhnologi serta berwawasan global.
            <li>MAJU DAN MANDIRI :</li> 
            Menjadikan masyarakat Desa Leuwinutug Cerdas, Terampil serta tangguh untuk menghadapi tantangan era global dalam menciptakan lapangan pekerjaan dan kewirausahaan.
            <li>AMANAH</li>
            Menyelenggarakan pemerintahan yang transparan, akuntabilitas, partisipatif dan responsive.
            <li>NYATA</li>
            Jadikan kemandirian Desa adalah kemampuan nyata Pemerintah dan masyarakat Desa Leuwinutug, dalam mengatur dan mengurus kepentingan masyarakat itu sendiri melalui aspirasi masyarakat.
        </ol> 
      </p>
      <p class="text-3xl font-semibold my-4">Struktur Desa</p>
      <img src="Struk Desa.jpg" alt=""/>
    </div>
  </main>
</template>

<style>
  body{
    background: #f1f1f1;
  }
</style>
