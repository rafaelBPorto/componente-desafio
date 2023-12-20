<template>
  <v-app>

    <!-- Menu Esquerda -->
    <v-navigation-drawer app>
      <Toolbar></Toolbar>
      <v-divider></v-divider>
      <MenuToolbar></MenuToolbar>
    </v-navigation-drawer>

    <!-- Conteudo -->
    <AppBar></AppBar>
    <Carroseul></Carroseul>

    <!-- Rodapé -->
    <Footer></Footer>
    
  </v-app>
</template>

<script>
import AppBar from '@/components/template/AppBar.vue'
import Carroseul from '@/components/widgets/Carroseul.vue'
import Footer from '@/components/template/Footer.vue'
import MenuToolbar from '@/components/template/MenuToolbar.vue'
import Toolbar from '@/components/template/Toolbar.vue'

export default {
  components:{
    AppBar,
    Carroseul,
    Footer,
    MenuToolbar,
    Toolbar,

  }
}
</script>
