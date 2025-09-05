<template>



  <NavBar />

  <BannerMain />

  <AboutUs />

  <Differentials />

  <More />

  <Footer />


</template>

<script lang="ts">

import { defineComponent } from 'vue'
import NavBar from '../components/NavBar.vue'
import BannerMain from '@/components/BannerMain.vue';
import AboutUs from '@/components/AboutUs.vue';
import Differentials from '@/components/Differentials.vue';
import More from '@/components/More.vue';
import Footer from '@/components/Footer.vue';

export default defineComponent({
  components: {
    NavBar,
    BannerMain,
    AboutUs,
    Differentials,
    More,
    Footer,
  }
})

</script>

<style>
.texto-principal {
  -webkit-text-stroke-width: 2px;
  /* largura da borda */
  -webkit-text-stroke-color: #ff7b16;
  /* cor da borda */
}

.texto-secundario {
  -webkit-text-stroke-width: 0.5px;
  /* largura da borda */
  -webkit-text-stroke-color: #9ffdff;
  /* cor da borda */
}

.bg-laranja-escuro {
  background-color: #ff6f00;
}

.bg-azul-claro {
  background-color: #9ffdff;
}

.text-laranja-escuro {
  color: #ff6f00;
}

.text-amarelo {
  color: #ffc500;
}

.text-azul-claro {
  color: #9ffdff;
}

.text-azul-escuro {
  color: #009ab6;
}

.text-laranja-escuro-hover:hover {
  color: #ff6f00;
}
</style>
