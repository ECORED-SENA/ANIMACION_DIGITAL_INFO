<template lang="pug">
section
  .banner-principal.mb-5
    .container.tarjeta.p-4.p-sm-5(
      :style="{'background-image': `url(${require('@/assets/curso/banner-princiapal.svg')})`}"
    )
      .row.justify-content-around.align-items-center
        .col-lg-7.col-xxl-6.banner-principal__info
          .banner-principal__programa
            .h1.mb-0 Animación 3D
          
          .h2 Información del programa
          .banner-principal__datos
            ul
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Nombre del programa: 
                p.banner-principal__datos__item__texto Animación 3D
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Código: 
                p.banner-principal__datos__item__texto 524703
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Total Horas: 
                p.banner-principal__datos__item__texto 3984  Horas
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Duración en meses: 
                p.banner-principal__datos__item__texto 27 Meses
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Modalidad: 
                p.banner-principal__datos__item__texto Virtual

        .d-none.d-lg-block.col-lg-5
          img(src="@/assets/curso/img1.png")
          //.video
            | <iframe data-v-1f9e4816="" width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen="allowfullscreen"></iframe>

  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 1. Presentación

    p El tecnólogo virtual en Animación 3D brinda a los aprendices la formación necesaria para incursionar en la industria audiovisual, animación y videojuegos; respondiendo así a la alta demanda nacional e internacional de personas capacitadas dentro del sector productivo de contenidos digitales.
      br
      br
      |Al realizar este programa de formación tendrá la capacidad y conocimiento necesarios para crear un guion cinematográfico, un storyboard, desarrollar el arte conceptual de un proyecto audiovisual, ejecutar procesos de producción 3D como: esculpir, modelar, texturizar, construir el rig, animar personajes, efectos visuales (VFX), iluminar y renderizar escenas; así como, componer, editar y entregar una pieza audiovisual con altos estándares de calidad, que le darán la oportunidad de entrar en el mercado laboral y mejorar su experiencia profesional.
      br
      br
      |El SENA cuenta con varios casos de éxito dentro de sus egresados del programa en Animación 3D; desde la co-producción con estudios de animación nacionales e internacionales, la ubicación laboral dentro de las principales productoras de videojuegos en Colombia, hasta la creación de nuevos estudios de desarrollo de contenidos digitales. 
      br
      br
      |No dejes pasar esta oportunidad. Te esperamos en esta grandiosa experiencia del mundo 3D.


  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 2. Justificación<br>del programa

    p Teniendo en cuenta la Ley Naranja del Gobierno Nacional, la cual tiene como objeto desarrollar, fomentar, incentivar y proteger las industrias creativas y de acuerdo con los datos del DANE, donde se evidencia un aumento del valor agregado por productos audiovisuales y de los ingresos por servicios de producción de películas y programas de televisión, estableciendo para el 2015 la contribución de las industrias creativas al PIB entre el 1,5% y el 3% (similar al sector minero).
      br
      br
      |El tecnólogo de formación titulada virtual en Animación 3D del SENA responde a la alta demanda por parte del sector productivo nacional e internacional de talento humano calificado en las áreas de las Tecnologías de la Información y la Comunicación (TIC). De igual manera, el programa ofrecido por el SENA cuenta con todos los elementos de formación profesional, sociales, tecnológicos y culturales, aportando como elementos diferenciadores de valor agregado metodologías de aprendizaje innovadoras, el acceso a tecnologías de última generación y una estructuración sobre métodos más que contenidos, lo que potencia la formación de ciudadanos librepensadores, con capacidad crítica, solidaria y emprendedora, factores que lo acreditan y lo hacen pertinente y coherente con su misión, innovando permanentemente de acuerdo con las tendencias y cambios tecnológicos y las necesidades del sector empresarial y de los trabajadores.


  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 3. Población<br>objetivo

    p El tecnólogo de formación titulada virtual en Animación 3D del SENA, está dirigido a todas las personas que desean incursionar en la industria audiovisual, haciendo uso de sus habilidades creativas, narrativas y gerenciales, con el fin de desarrollar proyectos animados en 3D, los cuales respondan a las necesidades y requerimientos de la industria.

  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 4. Estrategia<br>metodológica

    p Centrada en la construcción de autonomía para garantizar la calidad de la formación en el marco de la formación por competencias, el aprendizaje por proyectos y el uso de técnicas didácticas activas que estimulan el pensamiento para la resolución de problemas simulados y reales; soportadas en la utilización de las tecnologías de la información y la comunicación, integradas, en ambientes virtuales de aprendizaje, que en todo caso recrean el contexto productivo y vinculan al aprendiz con la realidad cotidiana y el desarrollo de las competencias. 
      br
      br
      |Igualmente, debe estimular de manera permanente la autocrítica y la reflexión del aprendiz sobre el que hacer y los resultados de aprendizaje que logra a través de la vinculación activa de las cuatro fuentes de información para la construcción de conocimiento:
    ul.lista-ul
      li
        i.lista-ul__vineta
        p El instructor - Tutor
      li
        i.lista-ul__vineta
        p El entorno
      li
        i.lista-ul__vineta
        p las TIC
      li
        i.lista-ul__vineta
        p El trabajo colaborativo

  //- Créditos
  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 Créditos

    
    .creditos
      div(
        v-for="(creditoKey, index) of Object.keys(creditosData)"
        :class="index != Object.keys(creditosData).length -1 ? 'mb-4' : ''" 
      )
        .creditos__titulo {{configTitulos[creditoKey]}}
        table
          tbody
            tr(
              v-for="(item, idx) of creditosData[creditoKey]" 
              :key="creditoKey+idx"
            )
              td.text-bold(colspan='2' v-html="renderText(item.nombre)")
              td(colspan='2' v-html="renderText(item.cargo)")
              td(colspan='3' v-html="renderText(item.centro)")

  Footer

</template>
<script>
export default {
  name: 'Inicio',
  data: () => ({
    configTitulos: {
      liderEquipo: 'ECOSISTEMA DE RECURSOS EDUCATIVOS DIGITALES',
      contenidoInstruccional: 'CONTENIDO INSTRUCCIONAL',
      desarrolloProducto:
        'DISEÑO Y DESARROLLO DE RECURSOS EDUCATIVOS DIGITALES',
      gestoresRepositorio: 'GESTORES DE REPOSITORIO',
    },
  }),
  computed: {
    creditosData() {
      return this.$config.creditos
    },
  },
  methods: {
    renderText(textObj) {
      let newText = ''
      if (Array.isArray(textObj)) {
        textObj.forEach((texto, index) => {
          newText += (index ? '<br/>' : '') + texto
        })
      } else {
        newText += textObj
      }
      return newText
    },
  },
}
</script>

<style lang="sass">
.creditos
  td, th
    border-color: $color-sistema-c
</style>
