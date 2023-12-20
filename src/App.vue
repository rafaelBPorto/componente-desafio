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
import AppBar from './AppBar.vue'
import Carroseul from './Carroseul.vue'
import Footer from './Footer.vue'
import MenuToolbar from './MenuToolbar.vue'
import Toolbar from './Toolbar.vue'

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
