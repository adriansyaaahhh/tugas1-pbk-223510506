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
    <template #heading>Data Diri</template>

   Perkenlkan nama saya ADRIANSYAH, saya lahir di kota
    <a href="https://id.wikipedia.org/wiki/Duri,_Mandau,_Bengkalis" target="_blank" rel="noopener">Duri</a>
    saya memiliki satu saudara kandung, saya kuliah di 
    <a href="https://uir.ac.id/" target="_blank" rel="noopener">Universitas Islam Riau</a>
    dan saat ini saya di jenjang semester 4,
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Hobby</template>

    Saya mempunya hobi salah satunya ialah bermain futsal,impian saya adalah bermain di liga pro indonesia,
    idola saya ialah 
    <a href="https://www.instagram.com/ardiansyah_runtuboy12/?hl=id" target="_blank" rel="noopener">Ardiansyah runtuboy</a>.
    saya juga memiliki hoby bermain alat musikyaitu gitar, idola saya dalam gitar ialah gitaris dewa 19 saat ini yaitu 
    <a href="https://id.yamaha.com/id/artists/a/andra_ramadhan.html" target="_blank" rel="noopener">Andra ramadhan</a> 
    saat dia membawakan gitar suasana begitu menyenangkan dan mempunyai ciri khas tersendiri
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Social Media</template>

    saya memiliki social media aktif yaitu instagram dengan nama
    <a href="https://www.instagram.com/adri_ansyaahh/?hl=id" target="_blank" rel="noopener">adri_ansyaahh</a>
  </WelcomeItem>

</template>
