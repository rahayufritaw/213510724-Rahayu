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
    <template #heading>Fungsi Bahasa Pemrograman Java Script</template>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>1. General Purpose</template>

    Saat ini JavaScript tidak hanya digunakan di sisi client (browser) saja lho. Semenjak adanya Node.js JavaScript dapat digunakan di luar dari browser. Dengan begitu kamu bisa mengembangkan back-end (server), console, program desktop, mobile, IoT, game, dan lainnya menggunakan JavaScript..
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>2. Mudah untuk Dipelajari</template>
    Setiap bahasa pemrograman memiliki tingkat kesulitan yang berbeda. Tingkat kesulitan bisa dilihat dari beberapa faktor. Menurut saya sih, syntax atau penulisan jadi salah satu faktor yang paling penting buat dipelajari. JS masih tergolong mudah dipelajari asalkan kamu serius dalam belajar dan selalu berani melakukan improvement atau bermain-main dengan itu. Masih belum percaya JS mudah dipelajari? Baiklah, ini perbandingan JS dengan beberapa bahasa lainnya. Contohnya dalam menampilkan “Hello World!” ya.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>3. Sangat Powerfull</template>

    Kamu harus tau! JavaScript termasuk bahasa pemrograman yang sudah mature, sifat inilah yang membuat JavaScript sangat powerfull. Dulu, website basisnya masih PHP atau mungkin saja kita pakai WordPress. Semua logika web dibuat dan bergantung pada sisi server. Inilah yang membuat web browser lebih statis.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>4. Banyak perusahaan yang mengimplementasikan JS</template>

    Siapa yang nggak mau kerja di startup? Iya pasti maulah, jika gajinya besar hehe. Kamu akan dibutuhkan perusahaan seperti startup jika serius untuk belajar JavaScript.
  </WelcomeItem>
</template>
