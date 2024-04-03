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
    <template #heading>Tentang Saya</template>

    <ul>
      <li>
        Nama : Muhammad Hafizh Fauzan Sangadji<br>
      </li>
      <li>  
        Golongan Darah : O<br>
      </li>
      <li>
        Asal : Teluk Bintuni<br>
      </li>
      <li>
        Link Instagram :<a href="https://www.instagram.com/fitkom_3/" target="_blank" rel="noopener">Klik Disini</a>
      </li>
    </ul>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Hobi</template>
    
    <ul>
      <li>
        Membaca
      </li>
      <li>
        Main Game
      </li>
    </ul>

  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Asal Sekolah</template>
    
    <ul>
      <li>
        Sekolah Dasar :<a href="https://sekolah.data.kemdikbud.go.id/index.php/chome/profil/705978d2-31f5-e011-b538-a71966992a83" target="_blank" rel="noopener">SD YAPIS FAKFAK</a>
      </li>
      <li>
        Sekolah Menengah Pertama :<a href="https://dapo.kemdikbud.go.id/sekolah/E0670E9EA74E1456C511" target="_blank" rel="noopener">SMP YAPIS 1 FAKFAK</a>, <a href="https://referensi.data.kemdikbud.go.id/tabs.php?npsn=69900189" target="_blank" rel="noopener">MTS BAITUL AMIN</a>
      </li>
      <li>
        Sekolah Menengah Atas :<a href="https://dapo.kemdikbud.go.id/sekolah/1D5A9D291C78CF6B3CD0" target="_blank" rel="noopener">SMK NEGERI 1 BINTUNI</a>
      </li>
    </ul>
  </WelcomeItem>

</template>
