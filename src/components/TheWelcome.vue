<script setup lang="ts">
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
    <template #heading>Biodata</template>

    Halo, perkenalkan nama saya M. Rafid Fathoni. Saya lahir di Batu Belah Kabuten Kampar Provinsi Riau, saya merupakan anak ketiga dari tiga bersaudara.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Riwayat Kuliah</template>

    Saya adalah seorang mahasiswa yang sedang menempuh pendidikan di Universitas Islam Riau di Kota Pekanbaru, fokus pada jurusan Teknik Informatika.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Hobi</template>

    hobi saya adalah bermain badminton dan juga bermain game. Keduanya merupakan kegiatan yang saya nikmati untuk mengisi waktu luang dan menjaga keseimbangan antara akademis dan rekreasi.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Minat dan Bakat</template>

    memiliki minat yang besar dalam bidang teknologi, khususnya dalam pengembangan perangkat lunak dan kecerdasan buatan.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>PENDIDIKAN</template>

  Riwayat Pendidikan:
  <ul>
  <li><a href="https://sekolah.data.kemdikbud.go.id/index.php/chome/profil/A037F3C8-2FF5-E011-99B7-318388A7AFFF" target="_blank" rel="noopener">SDN 028 Pematang Reba</a></li>
  <li><a href="https://sekolah.data.kemdikbud.go.id/index.php/chome/profil/70A65F71-8B18-E111-9EE1-8576CB2DD694" target="_blank" rel="noopener">SDN 97 Tanggamus</a></li>
  <li><a href="https://sekolah.data.kemdikbud.go.id/index.php/chome/profil/80FDF65F-0C26-E111-85C7-63BD9ED033DE" target="_blank" rel="noopener">SDN 97 Jambi</a></li>
  <li><a href="https://www.smpannamiroh.sch.id/" target="_blank" rel="noopener">SMP An-Namiroh Pekanbaru</a></li>
  <li><a href="https://man3pekanbaru.sch.id/" target="_blank" rel="noopener">MAN 3 Pekanbaru</a></li>
  <li><a href="https://uir.ac.id/profil" target="_blank" rel="noopener">Universitas Islam Riau</a></li>
</ul>
  </WelcomeItem>
</template>
