<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    
    
    .row.justify-content-around.fondo-recuadro.mb-5
      .col-1.col-md-3
        //vacio
      .col-lg-8.py-lg-5
        .row.justify-content-center
          .col-10.col-lg-auto.align-self-center
            figure.resnone
              img.mx-auto(src='@/assets/curso/intro/icono1.svg', alt='imagen ambiental', style='width: 66px;')
            figure.resnone-lg
              img.mx-auto(src='@/assets/curso/intro/img1.jpg', alt='imagen ambiental', style='width: 480px;')
          .col-auto.col-lg.p-4.p-lg-1
            .p-2(style='border-left: 4px solid #1D272B;')
              p.mb-0
                b(style="color: #008F85;") Apreciado aprendiz 
                b-none le damos la bienvenida a esta 
                b experiencia de aprendizaje diseñada para desarrollar conocimientos, habilidades y actitudes en relación con la presentación de la imagen natural del cuerpo de un fallecido, 
                b-none para empezar, se le invita a revisar el siguiente recurso educativo.
                
    
    p.mb-4 Como aprendiz se hace necesario pensar en la 
      b(style="color: #008F85;") tanatoestética 
      b como actividad articulada dentro del embalsamamiento y que se ejecuta después de la desinfección y preservación química del cadáver. 
      b-none Estos momentos anteriores siempre deben pensar que generar las condiciones físicas y químicas para los procedimientos cosmetológicos.
    
    .row.align-items-center.justify-content-center.mb-5
      .col-lg-7.mb-4.mb-lg-0
        .cajon.color-secundario.p-4.mb-4
          p.mb-0
            b(style="color: #008F85;") La estética de un cuerpo sin vida
            b-none es una sensación planeada para el ritual final de este. 
            b A veces quienes asisten a esta ceremonia fijan su mirada en los detalles de los aspectos físicos 
            b-none del fallecido, y esta 
            b acción será una imagen que quedará en la memoria de los deudos.
        
        p.mb-0 En el presente 
          b componente de formación se ha estructurado 
          b-none en torno a 
          b temáticas como  la estética de un cuerpo fallecido, las adecuaciones del cuerpo para la 
          b(style="color: #008F85;") tanatoestética y la cosmetología funeraria.  
          b-none Cabe mencionar que 
          b la estética del fallecido se realiza a partir de técnicas de maquillaje 
          b-none  en las que se busca la 
          b(style="color: #008F85;") naturalidad del fallecido, 
          b-none asemejándose a sus naturales y su tipo de piel. En ocasiones, 
          b las técnicas de estética contribuyen a enmendar daños visibles en el rostro causados por una enfermedad, accidentes o traumatismo, entre otros.
      
      .col-10.col-lg-5(data-aos="fade-left")
        figure
          img.mx-auto(src='@/assets/curso/intro/img2.svg' alt='Tanatoestética y cosmetología funeraria', style='width: 413px;')


    p Al considerar la <b><span class="cp">tanatoestética</span></b> como los detalles de la imagen del cadáver <b>como aprendiz y  tanatopractor debe comprender la ruta y experiencia de aprendizaje que se ha diseñado en este componente de formación para que <span class="cp">desarrolle conocimientos, habilidades y actitudes para presentar la imagen natural del cuerpo</span></b> de acuerdo con su estado y características.
    
    .row.align-items-center.justify-content-center
      .col-10.col-lg-5.mb-4.mb-lg-0(data-aos="fade-right")
        figure
          img(src='@/assets/curso/intro/img3.svg' alt='Traslado inicial en el que se recoge el falledido', style='width: 430px;')
      .col-lg-7
        p Cuando se realiza el 
          b traslado inicial, en el que se recoge el fallecido, es importante escuchar los requerimientos  de la familia 
          b-none o solicitantes del servicio funerario para que usted 
          b(style="color: #008F85;") proceda con los lineamientos estéticos, 
          b la ropa o pertenencias que entregan.
        .cajon.color-secundario.p-4
          p.mb-0 Con lo mencionado hasta aquí, 
            b(style="color: #008F85;") le damos la bienvenida a este ambiente de aprendizaje 
            b-none que lo llevará a conectar su experiencia con información e interacciones diseñadas desde videos, lecturas, interacciones con sus compañeros a través de la tecnología. Bienvenido.






</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass"></style>
