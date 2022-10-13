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
    <template #heading>About Me</template>

    My name is Yudhi Fadilah
    and iam curently studies at Universities Logistic and Business International, and then my major is D3 Infomatics Engineering. So, i was Graduate from the Senior High School at SMAN 1 CISARUA.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Programing Language</template>

    I can work with : <br>
    <a href="https://vuejs.org">Vue.js</a>
    <br>
    <a href="https://tailwindcss.com">Tailwind css</a>
    <br> 
    <a href="https://www.php.net">Php</a>
    <br> 
    <a href="https://id.wikipedia.org/wiki/HTML">Html</a> 
    <br />
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Languages</template>

    I can speak with several languages like :
    <br>
    <a>Bahasa</a>
    <br>
    <a>English</a>
    <br>
    <a>Deutsch</a>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Project & Design</template>

    
    I've been created a comunity website for <a href="https://yolommxv.my.id" target="_blank" rel="noopener">Yolo MMXV</a>
    <br>
    And i also, create a Template Instagram for a <a href="https://drive.google.com/file/d/1rCRW1cWFSR9o2loB2Wra_JsdtRhC-z_r/view?usp=sharing" target="_blank" rel="noopener"
      >Campus Organization</a>
  </WelcomeItem>
  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Contact Me</template>
    You can Contact me via :<br>
    A Whatsapp : <a href="https://api.whatsapp.com/send?phone=6285155294388&text=Hi,%20we're%20interesting%20with%20you." target="_blank" rel="noopener">Text Me!</a>
    <br>A Email : fayudhi@gmail.com
  </WelcomeItem>
</template>
