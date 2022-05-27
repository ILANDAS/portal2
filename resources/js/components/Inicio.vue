<template>
 <div>

    <main class="py-20" style="background:#ccc;">
          
              <Slidershow></Slidershow>
            
    </main>



    <!-- ACERCA DE NOSOSTROS -->
    <div class="pt-3 pb-3" style="background: linear-gradient(rgb(0 68 162 / 90%), rgba(255, 255, 255, 0.85)) 0% 0% / cover, url(./../img/sede-gobirno-regional.jpg);">
       <div class="container">
          <h4 class="text-center text-white">Acerca de nosotros </h4>
          <hr/>
          <div class="row mt-4">
             <div class="col-xs-4 col-sm-4 col-12  text-center mt-3">
                
                <div class="msn text-white ">
                  <div class="msn1">Misión</div>
                  <div class="msn2">Conducir y promover el desarrollo humano Integral y Sostenible de la Población del Departamento de Huánuco, con una gestión moderna, transparente, competitiva e inclusiva, brindand bienes y servicios de calidad, con énfasis ambiental y la reducción de riezgos
                  </div>
                </div>
                
             </div>
             <div class="col-xs-4 col-sm-4 col-12 text-center mt-3" >
                <img :src="ruta+'./../img/logocuadrado.jpg'" class="rounded-circle shadow" height="220">
             </div>
             <div class="col-xs-4 col-sm-4 col-12 col-md-4 text-center mt-3">
                <div class="msn text-white">
                <div class="msn1">Visión</div>
                <div class="msn2">Huánuco, territorio andino Amazónico integrado, que ha impulsado el desarrollo humano y la sostenibilidad de su economia, en base a la grandeza de su Biodiversidad y el respeto por la interculturalidad
                </div>
                </div>
             </div>
          </div>
       </div>
    </div>
   
    <!-- FIN ACERCA DE NOSOSTROS -->

      <!-- TRAMITES Y Servicios -->
    <div class="pt-3 mb-5">
       <div class="container">
          <h4 class="text-center">Trámites y Servicios</h4>
          <hr/>
          <div class="row mt-4 text-center ">
            <div class="col-6 col-md-2">
               <button class="btn btn-outline-danger boton">
                  <i class="fa-solid fa-file fa-3x"></i>
               <h5 class="text-uppercase pt-3">RESULTADO PROCOMPITE</h5>
               <p class="lh-1 textxs" >Accede a los resultados de PROCOMPITE</p></button>
            </div>

            <div class="col-6 col-md-2">
               <button class="btn btn-outline-primary boton">
                  <i class="fa-solid fa-user-circle fa-3x"></i>
               <h5 class="text-uppercase pt-3">SISTEMA DE GESTIÓN DIGITAL</h5>
               <p class="lh-1 fw-light textxs">Ingresa al Sistema de Gestión Digital</p></button>
            </div>

            <div class="col-6 col-md-2">
               <button class="btn btn-outline-primary boton">
                  <i class="fa-solid fa-file-signature fa-3x"></i>
               <h5 class="text-uppercase pt-3">DIRECTORIO INSTITUCIONAL</h5>
               <p class="lh-1 fw-light textxs">Accede a la Información Pública de los miembros de ls Institución</p></button>
            </div>

            <div class="col-6 col-md-2">
               <button class="btn btn-outline-primary boton">
                  <i class="fa-brands fa-gg-circle fa-3x"></i>
               <h5 class="text-uppercase pt-3">ACCESO A INTRANET</h5>
               <p class="lh-1 fw-light textxs">Accede al Intranet para todos los trabajadores del GOREHCO</p></button>
            </div>

            <div class="col-6 col-md-2">
               <button class="btn btn-outline-primary boton">
                  <i class="fa-solid fa-file-text fa-3x"></i>
               <h5 class="text-uppercase pt-3">FORMATO ÚNICO DE TRÁMITE</h5>
               <p class="lh-1 fw-light textxs">Accede al formato único de trámite del Gobierno Regional</p></button>
            </div>

            <div class="col-6 col-md-2">
               <button class="btn btn-outline-primary boton">
                  <i class="fa-solid fa-file-pdf fa-3x"></i>
               <h5 class="text-uppercase pt-3">NORMATIVA REGIONAL</h5>
               <p class="lh-1 fw-light textxs">Accede a la Normativa Regional del GOREHCO</p></button>
            </div>

            <div class="col-6 col-md-2">
               <button class="btn btn-outline-primary boton">
                  <i class="fa-solid fa-building-circle-check fa-3x"></i>
               <h5 class="text-uppercase pt-3">DOCUMENTOS DE GESTIÓN</h5>
               <p class="lh-1 textxs" >Accede a los Documentos de Gesión</p></button>
            </div>

            <div class="col-6 col-md-2">
               <button class="btn btn-outline-primary boton">
                  <i class="fa-solid fa-bullhorn fa-3x"></i>
               <h5 class="text-uppercase pt-3">ORDENANZAS REGIONALES</h5>
               <p class="lh-1 fw-light textxs">Entérate acerca de las ordenanzas regionales</p></button>
            </div>

            <div class="col-6 col-md-2">
               <button class="btn btn-outline-primary boton">
                  <i class="fa-solid fa-vcard fa-3x"></i>
               <h5 class="text-uppercase pt-3">NUESTRAS AUTORIDADES</h5>
               <p class="lh-1 fw-light textxs">Conoce a nuestras Autoridades</p></button>
            </div>

            <div class="col-6 col-md-2">
               <button class="btn btn-outline-primary boton">
                  <i class="fa-brands fa-users fa-3x"></i>
               <h5 class="text-uppercase pt-3">ACUERDOS DE CONSEJO</h5>
               <p class="lh-1 fw-light textxs">Infórmate acerca de los Acuerdos de Consejo</p></button>
            </div>

            <div class="col-6 col-md-2">
               <button class="btn btn-outline-primary boton">
                  <i class="fa-solid fa-computer fa-3x"></i>
               <h5 class="text-uppercase pt-3">CONSULTA DE OBRAS</h5>
               <p class="lh-1 fw-light textxs">Consulta las Obras realizadas por el Gobierno Regional</p></button>
            </div>

            <div class="col-6 col-md-2">
               <button class="btn btn-outline-primary boton">
                  <i class="fa-solid fa-eye fa-3x"></i>
               <h5 class="text-uppercase pt-3">REGISTRO DE VISTAS</h5>
               <p class="lh-1 fw-light textxs">Accede al registro de visitas a la Página</p></button>
            </div>

         </div>
       </div>
    </div>
    <!-- FIN DE TRAMITES Y SERVICIOS -->

        <!-- NOTICIAS -->
    <div class="pt-3 pb-3" style="background:#cfe2ff;">
       <div class="container">
          <h4 class="text-center">Noticias </h4>
          <hr/>
          <Slidernoticias/>
       </div>
          
    </div>
    <!-- FIN NOTICIAS -->
       <!-- PLATAFORMAS -->
    <div class="pt-3 pb-3" style="background:#ffff;">
       <div class="container">
          <h4 class="text-center">Plataformas </h4>
          <hr/>
          <div class="row mt-4">
             <div class="col-xs-4 col-sm-4 col-12  text-center mt-3">
                <div class="card card-widget widget-user-2">
                  <!-- Add the bg color to the header using any of the bg-* classes -->
                  <div class="widget-user-header bg-primary">
                    <!-- /.widget-user-image -->
                    <h3 class="widget-user-username">PLATAFORMAS</h3>
                    <h5 class="widget-user-desc">Trabajo remoto</h5>
                  </div>
                  <div class="card-footer p-0">
                    <ul class="nav flex-column">
                      <li class="nav-item">
                        <a href="laplicativos" class="nav-link">
                          Reuniones virtuales <span class="float-right badge bg-primary">3</span>
                        </a>
                      </li>
                      <li class="nav-item">
                        <a href="laplicativos" class="nav-link">
                          Plataformas sociales <span class="float-right badge bg-primary">2</span>
                        </a>
                      </li>
                      <li class="nav-item">
                        <a href="laplicativos" class="nav-link">
                          Plataforma de trabajos por actividades <span class="float-right badge bg-primary">3</span>
                        </a>
                      </li>
                      <li class="nav-item">
                        <a href="laplicativos" class="nav-link">
                          Escritorio remoto <span class="float-right badge bg-primary">3</span>
                        </a>
                      </li>
                      <li class="nav-item">
                        <a href="laplicativos" class="nav-link">
                          Conexión remoto <span class="float-right badge bg-primary">3</span>
                        </a>
                      </li>
                    </ul>
                  </div>
                </div>
             </div>

             <div class="col-xs-4 col-sm-4 col-12  text-center mt-3">
                <div class="card card-widget widget-user-2">
                  <!-- Add the bg color to the header using any of the bg-* classes -->
                  <div class="widget-user-header bg-primary">
                    
                    <!-- /.widget-user-image -->
                    <h3 class="widget-user-username">OTROS ENLACES</h3>
                    <h5 class="widget-user-desc">Institucionales</h5>
                  </div>
                  <div class="card-footer p-0">
                    <ul class="nav flex-column">
                      <li class="nav-item">
                        <a href="laplicativos" class="nav-link">
                          Audiencias 
                        </a>
                      </li>
                      <li class="nav-item">
                        <a href="laplicativos" class="nav-link">
                          Diagnostico Situacional de Brechas de Infraestructura y Servicios en la Región Huánuco 2021-2023
                        </a>
                      </li>
                      <li class="nav-item">
                        <a href="laplicativos" class="nav-link">
                          Memoria Anual
                        </a>
                      </li>
                      <li class="nav-item">
                        <a href="laplicativos" class="nav-link">
                          Información de Gobierno Digital 
                        </a>
                      </li>
                    </ul>
                  </div>
                </div>
             </div>

             <div class="col-xs-4 col-sm-4 col-12  text-center mt-3">
                <div class="card card-widget widget-user-2">
                  <!-- Add the bg color to the header using any of the bg-* classes -->
                  <div class="widget-user-header bg-primary">
                    
                    <!-- /.widget-user-image -->
                    <h3 class="widget-user-username">PUBLICACIONES</h3>
                    <h5 class="widget-user-desc">Institucionales</h5>
                  </div>
                  <div class="card-footer p-0">
                    <ul class="nav flex-column">
                      <li class="nav-item">
                        <a href="laplicativos" class="nav-link">
                          Publicaciones(Planes,Revistas,etc) 
                        </a>
                      </li>
                      <li class="nav-item">
                        <a href="laplicativos" class="nav-link">
                          Programa Pro Compite 
                        </a>
                      </li>
                      <li class="nav-item">
                        <a href="laplicativos" class="nav-link">
                          Ambiental (Impacto Social-Ambiental) 
                        </a>
                      </li>
                      <li class="nav-item">
                        <a href="laplicativos" class="nav-link">
                          Publicaciones POI 
                        </a>
                      </li>
                      <li class="nav-item">
                        <a href="laplicativos" class="nav-link">
                          Publicaciones PEI 
                        </a>
                      </li>
                      <li class="nav-item">
                        <a href="laplicativos" class="nav-link">
                          Publicaciones PDRC 
                        </a>
                      </li>
                    </ul>
                  </div>
                </div>
             </div>
          </div>
       </div>
          
    </div>
    <!-- FIN PLATAFORMAS -->
       <!-- OTROS MEDIOS -->
    <div class="pt-3 pb-3" style="background:#cfe2ff;">
       <div class="container">
          <h4 class="text-center">Otros Medios</h4>
          <hr/>
          <div class="row mt-4 text-center ">
            <div class="col-6 col-md-2">
               <button class="btn btn-outline-primary boton">
               <h5 class="text-uppercase pt-3">Medios para la presentación de presuntas denuncias de  actos de corrupción</h5>
               </button>
            </div>

            <div class="col-6 col-md-2">
               <button class="btn btn-outline-primary boton">
               <h5 class="text-uppercase pt-3">FORMULARIOS ESTANDARIZADOS A UTILIZAR EN PROCEDIMIENTOS ADMINISTRATIVOS DE LA SUB DIRECCION DE PESQUERIA</h5>
               </button>
            </div>

            <div class="col-6 col-md-2">
               <button class="btn btn-outline-primary boton">
               <h5 class="text-uppercase pt-3"> Apendice N°2 - FORMATOS(ORGANO DE CONTROL INTERNO)</h5>
               </button>
            </div>

            <div class="col-6 col-md-2">
               <button class="btn btn-outline-primary boton">
               <h5 class="text-uppercase pt-3">LISTA DE PAGO DEUDA SOCIAL</h5>
               </button>
            </div>

            <div class="col-6 col-md-2">
               <button class="btn btn-outline-primary boton">
               <h5 class="text-uppercase pt-3">CURSOS Y BECAS DISPONIBLES ORCI</h5>
              </button>
            </div>

            <div class="col-6 col-md-2">
               <button class="btn btn-outline-primary boton">
               <h5 class="text-uppercase pt-3">TRÁMITES CON CLAVE SOL</h5>
              </button>
            </div>

            <div class="col-6 col-md-2">
               <button class="btn btn-outline-primary boton">
               <h5 class="text-uppercase pt-3">Transparencia y Lucha contra la Corrupción en el contexto de emergencia COVID-19</h5>
              </button>
            </div>

            <div class="col-6 col-md-2">
               <button class="btn btn-outline-primary boton">
               <h5 class="text-uppercase pt-3">NEUTRALIDAD POR PERIODO ELECTORAL</h5>
              </button>
            </div>


         </div>
       </div>
          
    </div>
    <!-- FIN OTROS MEDIOS -->
    <!-- VIDEOS -->
    <section id="anuncios">
    <div class="pt-3 pb-3" style="background:#ffff;">
       <div class="container">
          <h4 class="text-center">  Videos </h4>
          <hr/>
          <div id="carrusel_video" class="carousel slide" data-ride="carousel">
                    <ol class="carousel-indicators">
                        
                            <button type="button" data-bs-target="#carrusel_video" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1">
                            </button>

                            <button type="button" data-bs-target="#carrusel_video" data-bs-slide-to="1" aria-label="Slide 2">
                            </button>
                            
                            <button type="button" data-bs-target="#carrusel_video" data-bs-slide-to="2" aria-label="Slide 3">
                            </button>

                            <button type="button" data-bs-target="#carrusel_video" data-bs-slide-to="3" aria-label="Slide 4">
                            </button>
                        
                        
                    </ol>
                    <div class="carousel-inner" role="listbox">
                        
                            <div class="carousel-item active">
                                <div class="row align-items-center">
                                    <div class="col-md-6 text-center">
                                       <iframe width="560" height="315" src="https://www.youtube.com/embed/7AQnjKrdpyY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                                    </div>
                                    <div class="col-md-6">
                                        <h3 class="mb-3 text-primary mt-3">#Desarrollo</h3>
                                        <p class="text-justify">AGENCIA REGIONAL DE DESARROLLO POTENCIARÁ ECONOMÍA REGIONAL 💪</p>
                                    </div>
                                </div>
                            </div>
                        
                            <div class="carousel-item">
                                <div class="row align-items-center">
                                    <div class="col-md-6 text-center">
                                        <iframe width="560" height="315" src="https://www.youtube.com/embed/moBoLDBxscs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                                    </div>
                                    <div class="col-md-6">
                                        <h3 class="mb-3 text-primary mt-3">#Descentralización</h3>
                                        <p class="text-justify">PRONTO AGENCIA REGIONAL DE DESARROLLO EN HUÁNUCO 💯</p>
                                    </div>
                                </div>
                            </div>
                        
                            <div class="carousel-item">
                                <div class="row align-items-center">
                                    <div class="col-md-6 text-center">
                                        <iframe width="560" height="315" src="https://www.youtube.com/embed/C5dwGzYGhCw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                                    </div>
                                    <div class="col-md-6">
                                        <h3 class="mb-3 text-primary mt-3">#Territorio</h3>
                                        <p class="text-justify">GOBERNADOR RESPALDA LÍMITE SANTA VIRGINIA, PACHITEA</p>
                                    </div>
                                </div>
                            </div>
                        
                            <div class="carousel-item">
                                <div class="row align-items-center">
                                    <div class="col-md-6 text-center">
                                        <iframe width="560" height="315" src="https://www.youtube.com/embed/RZ4Izygd_7k" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                                    </div>
                                    <div class="col-md-6">
                                        <h3 class="mb-3 text-primary mt-3"> #Transparencia </h3>
                                        <p class="text-justify">XII CONSEJO DE MINISTROS DESCENTRALIZADO HUÁNUCO, RESULTADOS</p>
                                    </div>
                                </div>
                            </div>
                            
                    </div>
            
                    <div align="right" class="mt-2 p-2">
                        <button class="carrolser_control btn btn-info btn-sm btn-circle" type="button" data-bs-target="#carrusel_video" data-bs-slide="prev" style="right: 50px !important;margin-botom:-5px">
                            <span class="carousel-control-prev-icon " aria-hidden="true" style="width: 1rem !important; height: 1rem !important;"></span>
                            <span class="visually-hidden">Previous</span>
                        </button>
                        <button class="carrolser_control btn btn-info btn-sm ml-2 btn-circle" type="button" data-bs-target="#carrusel_video" data-bs-slide="next" style="right: 0px !important;">
                            <span class="carousel-control-next-icon" aria-hidden="true" style="width: 1rem !important; height: 1rem !important;"></span>
                            <span class="visually-hidden">Next</span>
                        </button>
                        
                        <a href="https://www.youtube.com/channel/UCFCS1cmD-9iM6nqetz-qXoA" class="btn btn-primary btn-sm" >Ver más videos <i class="fas fa-arrow-circle-right" aria-hidden="true"></i> </a>
                        
                    </div> 


                </div>

       </div>
          
    </div>
    </section>
    <!-- FIN VIDEOS -->


     <!-- UBICACIÓN-->
    <div class="pt-3 pb-3" style="background:#ffff;">
       <div class="container-fluid">
          <h4 class="text-center">Contáctanos </h4>
         
          <hr/>
             
            <div id="mapa-contactanos" class="p-3 pt-4 d-none d-md-block" >
              <table>
                 <tbody>
                    <tr>
                       
                       <td>
                          <h6> <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-geo-alt-fill" viewBox="0 0 16 16">
                           <path d="M8 16s6-5.686 6-10A6 6 0 0 0 2 6c0 4.314 6 10 6 10zm0-7a3 3 0 1 1 0-6 3 3 0 0 1 0 6z"/>
                           </svg> DIRECCIÓN </h6>
                             <div>
                                Calle Calicanto 145
                                <br>
                                Amarilis-Huanuco
                             </div>
                             <br>
                       </td>
                    </tr>
                    <tr>
                       <td>
                          <h6> <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-telephone-fill" viewBox="0 0 16 16">
                          <path fill-rule="evenodd" d="M1.885.511a1.745 1.745 0 0 1 2.61.163L6.29 2.98c.329.423.445.974.315 1.494l-.547 2.19a.678.678 0 0 0 .178.643l2.457 2.457a.678.678 0 0 0 .644.178l2.189-.547a1.745 1.745 0 0 1 1.494.315l2.306 1.794c.829.645.905 1.87.163 2.611l-1.034 1.034c-.74.74-1.846 1.065-2.877.702a18.634 18.634 0 0 1-7.01-4.42 18.634 18.634 0 0 1-4.42-7.009c-.362-1.03-.037-2.137.703-2.877L1.885.511z"/>
                          </svg> TELÉFONOS </h6>
                             <div>
                                +51 (062) 51-2124
                             </div>
                           <br>
                       </td>
                    </tr>
                    <tr>
                       <td>
                          <h6> <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-envelope-fill" viewBox="0 0 16 16">
                          <path d="M.05 3.555A2 2 0 0 1 2 2h12a2 2 0 0 1 1.95 1.555L8 8.414.05 3.555ZM0 4.697v7.104l5.803-3.558L0 4.697ZM6.761 8.83l-6.57 4.027A2 2 0 0 0 2 14h12a2 2 0 0 0 1.808-1.144l-6.57-4.027L8 9.586l-1.239-.757Zm3.436-.586L16 11.801V4.697l-5.803 3.546Z"/>
                          </svg> CORREOS</h6>
                             <div>
                                mesadepartesvirtual@regionhuanuco.gob.pe
                                <h6>Oficina de Secretaría general</h6>
                             </div>
                             <div>
                                sistemas@regionhuanuco.gob.pe
                                <br>
                                <h6>Sub Gerencia de Modernización y Transformación Digital</h6>
                             </div>
                             <br>
                       </td>
                    </tr>
                 </tbody>
              </table>
            </div>
            <div class="map-responsive">
               <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d1389.4704820193235!2d-76.23563653018458!3d-9.932625095755043!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x91a7c2fcae5899ab%3A0xdb74b5c9e67b6366!2sGobierno%20Regional%20Hu%C3%A1nuco!5e0!3m2!1ses-419!2spe!4v1649430178415!5m2!1ses-419!2spe" width="1300" height="500" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
            </div>
       </div>
    </div>
    <!-- FIN UBICACIÓN-->
      <!-- ENLACES EXTERNOS-->
    <div class="pt-3 pb-3" style="background:#cfe2ff;">
       <div class="container">
          <h4 class="text-center">Enlaces Externos </h4>
          <hr/>
          <SliderEnlaces/>
       </div>
    </div>
    <!-- FIN ENLACES EXTERNOS-->
 </div>
</template>

<script>
import Slidershow  from './CarrouselPublicidad'
import Slidernoticias  from './Carrouselnoticias'
import SliderEnlaces  from './CarrouselEnlaces'
// import axios from 'axios'
 export default {
     props:['ruta'],
   components:{Slidershow,Slidernoticias,SliderEnlaces}
   
 }

 
</script>



<style lang="css" scoped>


.sr-only{
   color: #2745a0;
}

.carousel {
    position: relative;
}

#anuncios .carousel-indicators {
    bottom: -75px;
}

.carousel-indicators {
    position: absolute;
    right: 0;
    bottom: 0;
    left: 0;
    z-index: 15;
    display: -ms-flexbox;
    display: flex;
    -ms-flex-pack: center;
    justify-content: center;
    padding-left: 0;
    margin-right: 15%;
    margin-left: 15%;
    list-style: none;
}

.masnoticias{
 align-content: center;
}


.msn {
        /* margin-left: 50px; */
        background: rgba(0, 68, 162, 0.5);
        box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
        border-radius: 50px;;
        /* width: 400px;
        height: 200px; */
        text-align: center;
        height: 185px;
        padding: 30px 5px;
        border: dashed 1px #e9ecec;

    }
      
    .msn1 {
        font-size: 20px;
        /* font-weight: bold; */
        /* color: #000000; */
        /* margin-top: 40px; */
    }
      
    .msn2 {
        font-size: 12px;
        /* font-weight: bold; */
    }

    .msn3 {
        /* margin-left: 50px; */
        background: rgba(0, 68, 162, 1);
        box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
        border-radius: 20px;;
        /* width: 400px;
        height: 200px; */
        text-align: center;
        height: 185px;
        padding: 15px 5px;

    }

.bg-primary {
    color: #FFF;
    background-color: rgba(0, 68, 162, 1) !important;
    }

hr{
   height: 3px;
  width: 10%;
  background-color:#2745a0;
  margin:0 auto;
  margin-bottom: 3px;
}

h4{
   font-weight: normal;
   font-weight: bold;
}
h6{
   color: aliceblue;
   font-weight: bold;
}
#mapa-contactanos {
    position: absolute;
    top: 1;
    left: 16.5%;
    z-index: 5;
    background-color: rgba(39, 69, 160, 0.80);
    width: 350px;
    height: 472px;
    line-height: 1.2;
}

#mapa-contactanos h2 {
    color: #FFF;
}

#mapa-contactanos table td {
    vertical-align: middle;
}

#mapa-contactanos table td i {
    color: #FFF;
    font-size: 1.3em;
    margin-right: 7px;
}

#mapa-contactanos table td label {
    color: #FFF;
    font-size: .8em;
}

#mapa-contactanos table td div {
    color: #FFF;
    font-size: .9em;
}

@media (max-width: 1024px) and (min-width: 900px) {
    #mapa-contactanos {
        left: 8%;
    }
}

@media (max-width: 899px) and (min-width: 768px) {
    #mapa-contactanos {
        left: 4%;
    }
}

@media (max-width: 767px) {
    #mapa-contactanos {
        left: 0;
    }
}

#seccion_contactanos table td {
    vertical-align: middle;
}

.map-responsive{
    overflow:hidden;
    padding-bottom:470px;
    position:relative;
    height:0;
}
.map-responsive iframe{
    left:0;
    top:0;
    /* height:50%; */
    width:100%;
    position:absolute;
}
.textxs{
font-size: .85em !important;
}

.boton{
   height: 185px;
    /* animation: all 0.3s ease-out; */
}

.nav-item:hover{
 background-color: rgb(230, 230, 243);
}

.row{
   padding: 20px;
    display: flex;
    flex-flow: row wrap;
    justify-content: space-between;
    align-items: center;
    width: 97%;
    margin: 0% auto;
}


</style>
