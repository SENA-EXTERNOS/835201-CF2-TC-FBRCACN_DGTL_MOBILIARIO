<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción

    .tarjeta.p-4.p-md-5.mb-5.fondo1.color-gris(data-aos="fade-down")
      .row.justify-content-end.align-items-center
        .col-md-5.order-md-first.order-sm-last
          p.py-3 Bienvenido a este recurso educativo, en el desarrollo de esta segunda parte del proceso de Fabricación digital de mobiliario, el aprendiz logrará adquirir las herramientas y habilidades básicas de los principales programas para el diseño mecánico, dibujo de piezas, partes y componentes; además de las funciones básicas y operaciones con éstos y lo que le permitia al diseñador, generar propuestas para el cliente. 
          p.py-3 También se revisará la manera en la cual las tecnologías 4.0 aportan en el proceso de diseño y visualización de productos para la generación de un mayor impacto en los mercados y clientes potenciales. Lo anterior con el objetivo de tener una calidad óptima en el proceso de preproducción para, así, trasmitirle al cliente adecuadamente el mensaje deseado.
          p.py-3 En el siguiente video se presenta de manera general, los temas que se tratarán en el componente formativo. <b>¡Muchos éxitos durante el aprendizaje!</b> 

        .col-md-6.mb-4.mb-md-0.order-md-last.order-sm-first(data-aos='fade-right')
          figure
            img(src="@/assets/curso/temas/introduccion/img-1.svg")

    
            .row.mt-5
    .col-12
      figure
        .video
          iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
          



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
