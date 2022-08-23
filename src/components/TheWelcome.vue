<script setup>
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
<div class="bungkus">
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Personal Profile</template>
  Raka Aditya Sumarno
  <br>
  Tempat, tanggal lahir : Depok, 25 Mei 2005
  <br>
  Alamat : Gg. Guan No.36, Curug, Kec. Cimanggis, Kota Depok, Jawa Barat 16455
  </WelcomeItem>

  
    <WelcomeItem>
      <template #heading>Education</template>
      2020-2023
      <br />
      <a href="https://smktarunabhakti.net/" target="_blank">SMK TARUNA BHAKTI, Depok</a>
       <br />
      FrontEnd Developer
    </WelcomeItem>
    <WelcomeItem>
      <template #icon>
        <EcosystemIcon />
      </template>
      <template #heading>Experience</template>
    <ul>
      <li>School Design</li>
      <li>Hospital Design</li>
      <li>Wedding Design</li>
      <li>Food Delivery Design</li>
    </ul>
    </WelcomeItem>
    <WelcomeItem>
      <template #icon>
        <CommunityIcon />
      </template>
      <template #heading>Language</template>
    <ul>
      <li>English</li>
      <li>Indonesia</li>
    </ul>
    </WelcomeItem>
    <WelcomeItem>
      <template #icon>
        <SupportIcon />
      </template>
      <template #heading>Contact</template>
    <h4>
      (+62) 895-3928-28575
    </h4>
    <h4>
      raka27275@gmail.com
    </h4>
      <h4>Ini Adalah link Github saya</h4><a target="_blank" href="https://github.com/RakaAditya01">Raka Aditya</a>.
    </WelcomeItem>
  </div>
</template>

<style>
  .bungkus{
    display: flex;
  }

  ul li {
    list-style: none;
  }
</style>
