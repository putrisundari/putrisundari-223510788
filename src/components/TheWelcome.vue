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
      <ToolingIcon />
    </template>
    <template #heading>History</template>

   saya pernah bekerja di Riau project selama 2 tahun terakhir.

    <br />

  </WelcomeItem>


  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Contact Person</template>

    Email: putrisundari838@student.uir.ac.id <br>
    Instagram : <a href="instagram.com/putrisndrr">@putrisndrr</a> <br>
    WhatsApp : +62+
    
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Skill</template>

    1. Public Speaking <br>
    2. Time Management <br>
    3. Script Writting 
  </WelcomeItem>
</template>
