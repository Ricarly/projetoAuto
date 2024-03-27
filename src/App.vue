<template>
  <v-app>
    <v-main class="conteudo">
      <v-container>
        <v-row class="d-flex justify-center flex-column align-center flex-md-row ">
          <v-col cols="6" md="4">
            <v-img src="./assets/logo_branca.png"></v-img>
          </v-col>
          <v-col cols="12" md="8">
            <v-img class="img" src="./assets/carro_auto.png"></v-img>
          </v-col>
        </v-row>
         <div class="d-flex justify-center flex-column align-center">
            <v-btn href="https://www.facebook.com/marketplace/profile/100040619602970/?ref=permalink&mibextid=dXMIcH" target="_blanc" class="botoes elevation-4" color="#1A237E" style="width: 800px;">
                <h2><v-icon color="#1E88E5" class="icone-face" icon="mdi-facebook"></v-icon></h2>
                <h2 class="titulo">Catálogo</h2>
            </v-btn>
            <v-menu>
              <template  v-slot:activator="{ props }">
                <v-btn v-bind="props" class="botoes elevation-4" color="#2E7D32" style="width: 800px;">
                  <h2><v-icon color="#00C853" class="icone-wats" icon="mdi-whatsapp"></v-icon></h2>
                  <h2 class="titulo">Whatsapps</h2>
                </v-btn>
              </template>
              <v-list class="bg-green-darken-3  d-flex justify-center flex-column align-center">
                <v-list-item><v-btn href="https://api.whatsapp.com/send?phone=5599992262481&text=Ol%C3%A1,%20vim%20pelo%20link%20da%20bio%20do%20Instagram,%20estou%20interessado%20em%20comprar%20meu%20seminovo." target="_blanc" variant="tonal"  density="compact"><h2 class="titulo">Imperatriz</h2></v-btn></v-list-item>
                <v-list-item>
                  <v-bottom-sheet inset>
                    <template v-slot:activator="{ props }">
                      <v-btn v-bind="props" variant="tonal"  density="compact"><h2 class="titulo">Açailândia</h2></v-btn>
                    </template>
                    
                    <v-list class="bg-green-darken-3 d-flex justify-center flex-column align-center">
                      <v-list-item><v-btn href="https://api.whatsapp.com/send/?phone=559991995455&text&type=phone_number&app_absent=0" target="_blanc" prepend-icon="mdi-phone-outline" style="width: 500px;" variant="tonal"  density="compact">Carlos Eduardo</v-btn></v-list-item>
                      <v-list-item><v-btn href="https://api.whatsapp.com/send/?phone=559991840075&text&type=phone_number&app_absent=0" target="_blanc" prepend-icon="mdi-phone-outline" style="width: 500px;" variant="tonal"  density="compact">Felipe</v-btn></v-list-item>
                      <v-list-item><v-btn href="https://api.whatsapp.com/send/?phone=559991369221&text&type=phone_number&app_absent=0" target="_blanc" prepend-icon="mdi-phone-outline" style="width: 500px;" variant="tonal"  density="compact">Raylana</v-btn></v-list-item>
                    </v-list>
                  </v-bottom-sheet>
                </v-list-item>
               
                
              </v-list>
          </v-menu>
            <v-btn href="https://www.instagram.com/borsoiauto/?namertag" target="_blanc" class="botoes elevation-4" color="#6A1B9A" style="width: 800px;">
              <h2><v-icon color="#AB47BC" class="icone-wats" icon="mdi-instagram"></v-icon></h2>
              <h2 class="titulo" >Instagram/imperatriz</h2>
            </v-btn>
            
            <v-btn href="https://www.instagram.com/borsoiauto_acailandia/?namertag" target="_blanc" class="botoes elevation-4" color="#6A1B9A" style="width: 800px;">
              <h2><v-icon color="#AB47BC" class="icone-wats" icon="mdi-instagram"></v-icon></h2>
              <h2 class="titulo" >Instagram/açailândia</h2>
            </v-btn>

            <v-btn href="https://maps.app.goo.gl/RsPZau8MrikEtbs3A" target="_blanc" class="botoes elevation-4" color="#C0CA33" style="width: 800px;">
              <h2><v-icon color="#B71C1C" class="icone-wats" icon="mdi-google-maps"></v-icon></h2>
              <h2 class="titulo" >Localização/Imperatriz</h2>
            </v-btn>

            <v-btn href="https://maps.app.goo.gl/rpovQUbmCKQaU1em9" target="_blanc" class="botoes elevation-4" color="#C0CA33" style="width: 800px;">
              <h2><v-icon color="#B71C1C" class="icone-wats" icon="mdi-google-maps"></v-icon></h2>
              <h2 class="titulo" >Localização/Açailândia</h2>
            </v-btn>
         </div>
          <div class="rodape d-flex flex-column aling-center">
            <v-img class="logo-empredimentos" src="./assets/logo-2-branca.png"></v-img>
            <h4 class="titulo-rodape" style="text-align: center;">Imperatriz-Ma</h4>
          </div>
      </v-container>
    </v-main>
  </v-app>
</template>

<script>
  //
</script>

<style>

  @import url('https://fonts.googleapis.com/css2?family=Raleway:ital,wght@0,100..900;1,100..900&display=swap');

  *{
    margin: 0;
    padding: 0;
    font-family: "Raleway", sans-serif;
  }
  .conteudo{
    height: 100%;
    background: rgb(0,0,0);
    background: linear-gradient(230deg, rgba(0,0,0,1) 0%, rgba(244,0,0,1) 100%, rgba(255,255,255,1) 100%);
  }
  .content{
    margin-left: 0px auto ;
    margin-right: 0px auto;
  }
  .icone-wats{
    padding-right: 40px;
  }
  .icone-face{
    padding-right: 40px;
  }
  .botoes{
    margin-top: 50px;
  }
  @media screen and (max-width:461px) {
    .titulo{
      font-size: 10px;
    }
  }
  .logo-empredimentos{
    height: 50px;
  }
  .rodape{
    margin-top: 100px;
  }
  .titulo-rodape{
    margin-top: 20px;
  }
</style>
