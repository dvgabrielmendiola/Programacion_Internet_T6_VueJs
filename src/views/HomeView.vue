<template>
  <v-app id = "home">
    <NavBar />
    <v-container fluid>
      <div class="head">
        <v-row>
          <v-col cols="4">
            <div style="position: relative" class="mt-16"> 
              <h1 class="">Hola! Soy</h1>
              <h1 class="text-yellow">Gabriel Mendiola</h1>
              <span class="">Técnico en Electrónica e ING. en Computación en proceso.</span>
              <br/>
              <v-btn title dark class="text-red mt-3" variant="outlined">Contactame!</v-btn>
            </div>
          </v-col>
          <v-col cols="2">
             <div style="position: absolute;
                  z-index: 9999;
                  bottom: 0;
                  margin-left: auto;
                  margin-right: auto;
                  left: 0;
                  right: 0;
                  text-align: center;">
                  <v-icon>fa fa-angle-double-down</v-icon>
              </div>
          </v-col>
          <v-col cols="6">
            <div style="position: relative;
                 z-index: 9999;" class="mt-16">
              <v-img src="src/img-1.png" contain max-height="300"></v-img>
            </div>
          </v-col>
        </v-row>
      </div>
      <v-col cols="12" class="mt-16" id="about">
        <div>
          <v-row>
            <v-col cols="12" sm="6">
              <div class="circle">
                <v-img src="src/img-2.png" max-height="300" class="img2"></v-img>
              </div>
            </v-col>
            <v-col cols="12" sm="6" xs="12" xm="12">

              <h4 class="mt-n4 textAbout">Estudiante de ING. en Computación & Tecnico en Electronica.</h4>
              <p class="text-grey textAbout">Hola! Soy Gabriel Mendiola, un apasionado de la electrónica y las ciencias computacionales, actualmente cursando mi sexto semestre de ingeniería en computación. Mi formación técnica en electrónica me ha brindado una sólida base en diseño de circuitos y sistemas electrónicos, mientras que mi estudio de ingeniería en computación me ha permitido explorar mi interés en la programación y el desarrollo de software. Mi objetivo es combinar estas habilidades para crear soluciones tecnológicas innovadoras.</p>
              <br/>
              <p class="text-grey textAbout">Mi meta es especializarme en el diseño de sistemas embebidos, implementando soluciones eficientes y seguras para dispositivos electrónicos en diversos campos como la robótica, la automatización y la Internet de las cosas (IoT).</p>
            </v-col>
          </v-row>
        </div>
      </v-col>
      <div class="text-center mt-4">
        <h2>Proyectos</h2>
      </div>
        <v-col cols="12" class="padd" id="projects">
          <div class="first" id="project">
            <v-row> 
              <v-col cols="12">
                <div class="child">
                  <v-btn icon="fas fa-bolt" color="#fbdf7e"></v-btn>
                  <h3 class="ml-3 mt-4">Automatización</h3>
                  <p class="text-grey ml-3 mt-4 text-caption">
                    Diseño, implementación y mantenimiento de sistemas automatizados en una amplia variedad de aplicaciones.
                  </p>
                </div>

                <div class="child">
                  <v-btn icon="fas fa-network-wired" color="#fbdf7e"></v-btn>
                  <h3 class="ml-3 mt-4">Redes de computadoras</h3>
                  <p class="text-grey ml-3 mt-4 text-caption">
                    Diseño de la arquitectura de red, coordinación de la configuración y supervición del equipo de implementación de redes empresariales seguras.
                  </p>
                </div>

                <div class="child">
                  <v-btn icon="fas fa-database" color="#fbdf7e"></v-btn>
                  <h3 class="ml-3 mt-4">Bases de datos</h3>
                  <p class="text-grey ml-3 mt-4 text-caption">
                    Diseño y desarrollo de bases de datos eficientes y seguras para empresas.
                  </p>
                </div>

                <div class="child">
                  <v-btn icon="fas fa-atom" color="#fbdf7e"></v-btn>
                  <h3 class="ml-3 mt-4">Diseño Web</h3>
                  <p class="text-grey ml-3 mt-4 text-caption">
                    Diseñó de interfaces de usuario atractivas y funcionales que incorporaba las mejores prácticas de diseño web responsivo.
                  </p>
                </div>
              </v-col>
            </v-row>
          </div>
        </v-col>
        <v-col cols="12" id="hireN">
          <div class="hire">
            <v-row>
              <v-col cols="12" sm="8" >
                <h1 class="">Contratame!</h1>
                <p class="text-grey">
                  Considero que soy el candidato ideal para formar parte de tu equipo. Mi enfoque y pasión por la electrónica y la ingeniería en computación, respaldados por mi formación académica y experiencia práctica, hacen que sea una elección sólida para contribuir al éxito de tu empresa o proyecto. 
                </p>
              </v-col>
              <v-col cols="12" sm="4">
                <v-btn color="red" class="mt-12">Contratame!</v-btn>
              </v-col>
            </v-row>
          </div>
        </v-col>
        <v-col cols="12" sm="12" class="px-16" id="contact">
          <v-row>
            <v-col cols="12" sm="5">
              <div class="child">
                <h1>Contacto</h1>
                <v-row>
                  <v-col cols="2">
                    <v-btn icon="fas fa-map-marker-alt" class="mt-1" variant="outline"></v-btn>
                  </v-col>
                  <v-col cols="10">
                    <span class="text-caption" style="margin-right: rem!important;">Blvd. Marcelino García Barragán #1421,<br/> esq Calzada Olímpica, C.P. 44430, Guadalajara, <br/> Jalisco, México.</span>
                    <br>
                  </v-col>  
                 </v-row>
                 <v-row>
                  <v-col cols="2">
                    <v-btn icon="fas fa-phone-alt" style="margin-left: .5rem;" variant="outline"></v-btn>
                  </v-col>
                  <v-col cols="10" class="mt-3">
                    <span class="text" style="margin-right: 4rem!important;">3344556677</span>
                    <br>
                  </v-col>  
                 </v-row>
                 <v-row>
                  <v-col cols="2">
                    <v-btn icon="fas fa-envelope" style="margin-left: .5rem;" variant="outline"></v-btn>
                  </v-col>
                  <v-col cols="10" class="mt-3">
                    <span class="text" style="margin-right: 4rem!important;">gabriel@gmail.com</span>
                    <br>
                  </v-col>  
                 </v-row>
              </div>
            </v-col>
            <v-col cols="12" sm="6">
            <h1 class="mt-8">Enviame un mensaje!</h1>
            <v-divider></v-divider>
            <span class="text-caption"
              >Estoy dispuesto a escucharte, ¡cuenta tus dudas!</span
            >
            <v-row class="mt-10">
              <v-col cols="12" sm="6">
                <v-text-field
                  label="Nombre"
                  persistent-hint
                  variant="outlined"
                ></v-text-field>
              </v-col>
              <v-col cols="12" sm="6">
                <v-text-field
                  label="Número de contacto"
                  persistent-hint
                  variant="outlined"
                ></v-text-field>
              </v-col>
            </v-row>
            <v-textarea
              label="Mensaje"
              persistent-hint
              variant="outlined"
            ></v-textarea>
            <v-btn color="#FBDF7E" class="mt-2">Enviar</v-btn>
          </v-col>
          </v-row>
        </v-col>
    </v-container>
    <footerView />

  </v-app>
</template>

<script>
import { defineComponent } from 'vue';

// Components
import NavBar from '../components/navBar.vue';
import footerView from '@/components/footerView.vue';

export default defineComponent({
  name: 'HomeView',
  components: {
    NavBar,
    footerView
  },
});
</script>

<style scoped>
  .v-container {
    padding: 16px 0;
  }
  .head {
    position: relative;
    text-align: center;
    padding: 12px;
    margin-bottom: 6px;
    height: 400px;
    width: 100%;
    color: whitesmoke;
  }

  .head::before {
    content: " ";
    position: absolute;
    top: 0;
    left: 0;
    height: 100%;
    width: 50%;
    background: black;
    transform: skew(0deg, 5deg);
  }
  .head::after {
    content: " ";
    position: absolute;
    top: 0;
    right: 0;
    height: 100%;
    width: 50%;
    background: black;
    transform: skew(0deg, -5deg);
  }

  .circle {
  display: block;
  margin-left: 19%;
  margin-top: 1vh;
  width: 60%; 
  max-width: 500px; 
  height: auto; 
  max-height: 50vh; 
  background-color: #fbdf7e;
  border-radius: 50%;
}

.img2 {
  padding-top: 55%;
}

.textAbout {
  text-align: justify;
  font-size: 17px;
  margin: 15px;
}

.first {
  width: 100%;
  text-align: center;
  padding: 1rem 1rem;
}

.child {
  display: inline-block;
  padding: 2rem 1rem;
  vertical-align: middle;
  text-align: center;
}

.imgHover {
  padding: 0 200px;
}

.hire {
  width: 100%;
  padding: 0 50px;
  background-color: #e9e9e9;
  text-align: center;
  margin-top: -15px;
  margin-bottom: 15px;
}


</style>


