<script setup>
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Biografi</template>

    Saya lahir di Kuntu, 26 Juli 2004.
    <a href="https://www.instagram.com/daztyndaffa_/" target="_blank" rel="noopener">official Account</a>
    Saya memulai sekolah dasar di SD 002 Kuntu. Setelah itu saya melanjutkan sekolah menengah pertama di MTsN 7 Kampar, dan sekolah menengah Atas di SMA N 2 Kampar kiri. Untuk sekarang saya sedang berkuliah di Universitas Islam Riau jurusan Teknik Informatika 
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Alamat</template>

    Saya berasal dari desa Kuntu, Kampar Kiri, Kampar, Riau, Indonesia
    <a href="https://www.google.com/maps/place/Kuntu+Darussalam,+Kec.+Kampar+Kiri,+Kabupaten+Kampar,+Riau/@-0.0956841,101.1571593,14z/data=!3m1!4b1!4m6!3m5!1s0x2e2a84c6a4f31c4f:0xe0229122df9bf902!8m2!3d-0.0961829!4d101.178725!16s%2Fg%2F12hhhqcx5?entry=ttu" target="_blank" rel="noopener">info</a>.
    Untuk Sekarang saya sedang stay di Kubang Jaya, Jalan Rambah Raya.<a href="https://www.google.com/maps/place/Jl.+Rambah+Raya,+Kubang+Jaya,+Kec.+Siak+Hulu,+Kabupaten+Kampar,+Riau+28293/@0.4170694,101.4095338,17z/data=!3m1!4b1!4m6!3m5!1s0x31d5a669d1b3289b:0xf1881b9313594dd6!8m2!3d0.417064!4d101.4121087!16s%2Fg%2F1pzwbgd9k?entry=ttu" target="_blank" rel="noopener">info</a>.
    <br />
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Hobi</template>

    Hobi saya bermain game console dan mobile. Untuk Game console biasanya saya suka bermain game Racing ataupun Action. Biasanya saya suka bermain game RDR 2 ataupun NFS.
    <a href="https://www.rockstargames.com/reddeadredemption2/" target="_blank" rel="noopener">Info</a>. Untuk Game mobile saya suka bermain Mobile Legends ataupun PUBG.<a href="https://m.mobilelegends.com/en" target="_blank" rel="noopener">Mobile Legends</a>.<a href="https://www.pubgmobile.com/id/home.shtml" target="_blank" rel="noopener">PUBG</a>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Skill</template>
    Semenjak menimbah ilmu dari Prodi Teknik Informatika UIR, saya menguasai beberapa bahasa pemrograman. Seperti :
    <ul>
      <li><a href="https://www.w3schools.com/cpp/cpp_intro.asp#:~:text=C%2B%2B%20is%20an%20object%2Doriented,fun%20and%20easy%20to%20learn!" target="_blank" rel="noopener">C++</a></li>
      <li><a href="https://www.java.com/en/" target="_blank" rel="noopener">Java</a></li>
      <li><a href="https://www.python.org/" target="_blank" rel="noopener">Python</a></li>
      <li><a href="https://www.javascript.com/" target="_blank" rel="noopener">Python</a></li>
      <li><a href="https://id.wikipedia.org/wiki/HTML" target="_blank" rel="noopener">HTML</a></li>
      <li><a href="https://en.wikipedia.org/wiki/CSS" target="_blank" rel="noopener">CSS</a></li>
    </ul>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Universitas</template>

    Sebagai kampus tertua di Provinsi Riau yang berdiri sejak 1962 kini UIR telah melahirkan dan mendidik ribuan pionir bangsa berwawasan global.
    <a href="https://uir.ac.id/" target="_blank" rel="noopener">Read More</a>.
  </WelcomeItem>
</template>
