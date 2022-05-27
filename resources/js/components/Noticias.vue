<template>
 <div>

     <div class="mt-4">
        
         <h1 class="text-center text-secondary">Noticias</h1>
         <hr>

     </div>
     <!-- CARRUSEL MAIN -->
      <div class="container">
                <div id="carouselExampleDark" class="carousel carousel-dark slide" data-bs-ride="carousel">
                <div class="carousel-indicators">
                    <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
                    <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="1" aria-label="Slide 2"></button>
                    <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="2" aria-label="Slide 3"></button>
                </div>
                <div class="carousel-inner" style="max-width: 1300px; height: 500px; margin: auto; object-fit: cover;">
                    <div class="carousel-item active" data-bs-interval="10000" >
                            <div class="content_item">
                                <img :src="ruta+'./../img/noticia1.jpg'" class="d-block w-100" alt="..." style="object-fit: cover;" >
                            </div>
                        <div class="carousel-caption d-none d-md-block">
                           <hr>
                           <h4 style="margin-top:10px;">GOREHCO Y MIDIS ARTICULAN PARA REDUCIR BRECHAS SOCIALES EN SECTORES</h4>
                        </div>
                    </div>

                    <div class="carousel-item">
                        <div class="content_item">
                        <img :src="'../'+ruta+'./../img/noticia2.jpg'" class="d-block w-100" alt="...">
                        </div>
                        <div class="carousel-caption d-none d-md-block" >
                            <hr>
                            <h4>CAPACITAN A PRODUCTORES PARA PLANIFICACIÓN DE VENTAS EN SAN MARCOS - UMARI</h4>
                        </div>
                    </div>
                    <div class="carousel-item">
                        <div class="content_item">
                        <img :src="'../'+ruta+'./../img/noticia3.jpg'" class="d-block w-100" alt="...">
                        </div>
                        <div class="carousel-caption d-none d-md-block" >
                            <hr>
                            <h4>DIVERSAS AUTORIDADES DE HUAMALÍES EN CONJUNTO CON EL GOBERNADOR REGIONAL SOSTIENEN ENTREVISTA CON VICEMINISTRO DE TRANSPORTES, PROVÍAS DESCENTRALIZADO Y PROVÍAS NACIONAL</h4>
                        </div>
                    </div>
                </div>

                <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleDark" data-bs-slide="prev" >
                    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                    <span class="visually-hidden">Previous</span>
                </button>

                <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleDark" data-bs-slide="next" >
                    <span class="carousel-control-next-icon" aria-hidden="true"></span>
                    <span class="visually-hidden">Next</span>
                </button>
                </div>
                </div>
            <!-- FIN DE CARRUSEL -->
            <!-- NEW-->
               <section class="flex-container">
                   <div class="module-head">
                      <h1 style="color:blue"> ACTUALIDAD </h1>
                      <span class="module-filter"></span>
                   </div>
                   <div class="main-post">
                      <div class="main-post">
		                   <article id="post-74395" class="post-74395 post type-post status-publish format-standard has-post-thumbnail hentry category-actualidad category-ultimas-noticias tag-hostigamiento-sexual tag-poder-judicial tag-pucp et-has-post-format-content et_post_format-et-post-format-standard">
			               <div class="header">
			                    <a href="http://gestionportales.regionhuanuco.gob.pe/storage/" title="AGENCIA AGRARIA LEONCIO PRADO CAPACITA A CACAOTEROS DE FILADELFIA – HUACAYBAMBA" class="featured-image">
				                <img data-lazyloaded="1" src="http://gestionportales.regionhuanuco.gob.pe/storage/" data-src="http://gestionportales.regionhuanuco.gob.pe/storage/" alt="Jueza condena a exalumna que denunció hostigamiento sexual contra profesor Luis Jaime Castillo" data-ll-status="loaded" class="entered litespeed-loaded"><noscript><img src="https://wayka.pe/wp-content/uploads/2022/05/FOTO_24052022_PJ-627x376.jpg.webp" alt="Jueza condena a exalumna que denunció hostigamiento sexual contra profesor Luis Jaime Castillo" /></noscript><span class="et_pb_extra_overlay et_pb_inline_icon" data-icon=""></span>
			                    </a>			</div>
			               <div class="post-content">
								<h2 class="entry-title"><a class="et-accent-color" style="color:#f29e1a;" href="http://gestionportales.regionhuanuco.gob.pe/storage/">Jueza condena a exalumna que denunció hostigamiento sexual contra profesor Luis Jaime Castillo</a></h2>
			               <div class="post-meta vcard">
					            <p><span class="updated">24 May, 2022</span> | <a href="https://wayka.pe/actualidad/" rel="tag">Actualidad</a>, <a href="https://wayka.pe/actualidad/ultimas-noticias/" rel="tag">Últimas Noticias</a></p>
				           </div>
								<div class="excerpt entry-summary">
									<p>Con el objetivo de fortalecer las capacidades técnicos-productivos de los productores de cacao, la Agencia Agraria Leoncio Prado desarrolló el curso de capacitación “Manejo Técnico del Cultivo de Cacao”...</p>
								</div>
			</div>
		</article>
	</div>
                   </div>
                   <ul class="posts-list">
                     
                   </ul>

               </section>

            <!-- NEW-->
             
            <!-- NOTICIAS DE ACTUALIDAD -->
           
            <div class="pt-3 pb-3">
                <div class="container">
                    <div class="actualidad">
                        <div class="title-box">
                        <h4 class="text-center">ACTUALIDAD</h4>
                        </div>
                        <div class="flex-container">
                        <div class="col">
                              <img :src="'../'+ruta+'./../img/noticia1.jpg'" height="400">
                              <h3>GOREHCO Y MIDIS ARTICULAN PARA REDUCIR BRECHAS SOCIALES EN SECTORES</h3>
                              <h6>18 de ABRIL 2022</h6>
                              <router-link :to="'/internoticias'" class="btn btn-outline-primary">Ver Más</router-link>
                        </div>
                        <div class="col">
                            <div class="col">
                                <div class="row">
                                    <div class="col">
                                         <img :src="'../'+ruta+'./../img/noticia2.jpg'" height="200">
                                    </div>
                                    <div class="col">
                                         <h5>CAPACITAN A PRODUCTORES PARA PLANIFICACIÓN DE VENTAS EN SAN MARCOS - UMARI</h5>
                                         <h6>18 de ABRIL 2022</h6>
                                         <a href="#" class="btn btn-outline-primary btn-sm">Ver Más</a>
                                    </div>
                                </div>
                            </div>
                            <div class="col">
                                <div class="row">
                                    <div class="col">
                                         <img :src="'../'+ruta+'./../img/noticia3.jpg'" height="200">
                                    </div>
                                    <div class="col">
                                         <h5>CAPACITAN A PRODUCTORES PARA PLANIFICACIÓN DE VENTAS EN SAN MARCOS - UMARI</h5>
                                         <h6>18 de ABRIL 2022</h6>
                                         <a href="#" class="btn btn-outline-primary btn-sm">Ver Más</a>
                                    </div>
                                </div>
                            </div>
                            <div class="col">
                                <div class="row">
                                    <div class="col">
                                         <img :src="'../'+ruta+'./../img/noticia4.jpg'" height="200">
                                    </div>
                                    <div class="col">
                                         <h5>CAPACITAN A PRODUCTORES PARA PLANIFICACIÓN DE VENTAS EN SAN MARCOS - UMARI</h5>
                                         <h6>18 de ABRIL 2022</h6>
                                         <a href="#" class="btn btn-outline-primary btn-sm">Ver Más</a>
                                    </div>
                                </div>
                            </div>
                            <br>
                            <a href="#" class="btn btn-primary">Ver Más Noticias</a>
                            <br>
                        </div>
                        </div>
                    </div>
                </div>
            </div>
            <!-- FIN DE NOTICIAS DE ACTUALIDAD -->
               <!-- INVESTIGACIÓN-->
            <div class="pt-3 pb-3">
                <div class="container">
                    <div class="actualidad">
                        <div class="title-box1">
                        <h4 class="text-center">INVESTIGACIÓN</h4>
                        </div>
                        <div class="row">
                        <div class="col">
                              <img :src="'../'+ruta+'./../img/noticia1.jpg'" height="400">
                              <h3>GOREHCO Y MIDIS ARTICULAN PARA REDUCIR BRECHAS SOCIALES EN SECTORES</h3>
                              <h6>18 de ABRIL 2022</h6>
                              <a href="#" class="btn btn-outline-danger">Ver Más</a>
                        </div>
                        <div class="col">
                            <div class="col">
                                <div class="row">
                                    <div class="col">
                                         <img :src="'../'+ruta+'./../img/noticia2.jpg'" height="200">
                                    </div>
                                    <div class="col">
                                         <h5>CAPACITAN A PRODUCTORES PARA PLANIFICACIÓN DE VENTAS EN SAN MARCOS - UMARI</h5>
                                         <h6>18 de ABRIL 2022</h6>
                                         <a href="#" class="btn btn-outline-danger btn-sm">Ver Más</a>
                                    </div>
                                </div>
                            </div>
                            <div class="col">
                                <div class="row">
                                    <div class="col">
                                         <img :src="'../'+ruta+'./../img/noticia3.jpg'" height="200">
                                    </div>
                                    <div class="col">
                                         <h5>CAPACITAN A PRODUCTORES PARA PLANIFICACIÓN DE VENTAS EN SAN MARCOS - UMARI</h5>
                                         <h6>18 de ABRIL 2022</h6>
                                         <a href="#" class="btn btn-outline-danger btn-sm">Ver Más</a>
                                    </div>
                                </div>
                            </div>
                            <div class="col">
                                <div class="row">
                                    <div class="col">
                                         <img :src="'../'+ruta+'./../img/noticia4.jpg'" height="200">
                                    </div>
                                    <div class="col">
                                         <h5>CAPACITAN A PRODUCTORES PARA PLANIFICACIÓN DE VENTAS EN SAN MARCOS - UMARI</h5>
                                         <h6>18 de ABRIL 2022</h6>
                                         <a href="#" class="btn btn-outline-danger btn-sm">Ver Más</a>
                                    </div>
                                </div>
                            </div>
                            <br>
                            <a href="#" class="btn btn-danger" style="align-content: flex-end;">Ver Más Artículos de Investigación</a>
                            <br>
                        </div>
                        </div>
                    </div>
                </div>
            </div>
            <!-- FIN DE INVESTIGACIÓN -->
    </div>

</template>

<script>
 import Header  from './Header'
 export default {
     props:['ruta'],
   components:{Header}
 }
</script>

<style lang="css" scoped>

.module-head, .tabbed-post-module .tabs{
        background: #fff;
    width: 100%;
    border-bottom: 1px solid rgba(0,0,0,.1);
    padding: 15px 20px;
    -webkit-box-sizing: border-box;
    box-sizing: border-box;
    line-height: 1;
}

.flex-container {
    padding: 20px;
    display: flex;
    flex-flow: row wrap;
    justify-content: space-between;
    align-items: center;
    width: 97%;
    margin: 0% auto;
}

.title-box {
    box-shadow: 1px;
    background-color: #1a368b;
    color: #ffffff;
    font-weight: bold;
   border-radius: 10px;
}
.title-box1 {
    box-shadow: 1px;
    background-color: #E73434;
    color: #ffffff;
    font-weight: bold;

   border-radius: 10px;
}
.actualidad{

    border-radius: 10px;
    box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
}
h1{
   font-weight: normal;
   font-weight: bold;
   color: aliceblue;
}

hr{
   height: 3px;
  width: 10%;
  background-color:#ffffff;
  margin:0 auto;
  margin-bottom: 3px;
}
.container {
    top: 0;
    left: 0;
    min-height: 500px;
    height: 50%;
    display: flex;
}

h4{
   font-weight: normal;
   font-weight: bold;
   color: aliceblue;
}

.carouselExampleDark {
    height: 50%;
}

.carousel-item ::before {
    content: '';
    width: 100%;
    height: 100%;
    position: absolute;
    top: 0;
    bottom: 0;
    background: linear-gradient(to bottom, rgba(255,0,0,0),rgba(39, 69, 160, 0.90));
    object-fit: cover;
}

</style>
