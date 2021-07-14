<template lang="pug">
section
  .banner-principal.mb-5
    .container.tarjeta.p-4.p-sm-5(
      :style="{'background-image': `url(${require('@/assets/curso/banner-princiapal.svg')})`}"
    )
      .row.justify-content-around.align-items-center
        .col-lg-7.col-xxl-6.banner-principal__info
          .banner-principal__programa
            .h1.mb-0 Tecnólogo Virtual en Animación Digital
          
          .h2 Información del programa
          .banner-principal__datos
            ul
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Nombre del programa: 
                p.banner-principal__datos__item__texto Tecnólogo Virtual en Animación Digital
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Código: 
                p.banner-principal__datos__item__texto 513601
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Total Horas: 
                p.banner-principal__datos__item__texto 3984 Horas
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Duración en meses: 
                p.banner-principal__datos__item__texto  27 meses
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

    p El programa Tecnólogo Virtual en Animación Digital ofrece a los aprendices la formación necesaria para realizar productos animados, haciendo uso de diferentes técnicas de animación en formato digital siguiendo y respondiendo a los estándares y necesidades del sector productivo de la industria del entretenimiento digital.
      br
      br
      |Al término de este programa, usted podrá desempeñarse de manera pertinente y competente en cualquiera de las fases de producción de un proyecto audiovisual que involucre técnicas de animación 2D, creando productos como; guion literario, storyboard, animatic, piezas de arte conceptual, personajes animados, motion graphics, efectos y procesos como animación, postproducción y edición. Adicional, podrá desarrollar una propuesta económica costeando las necesidades y pormenores de un proyecto animado.
      br
      br
      |El SENA es una entidad que se articula con el sector laboral, brindando así múltiples oportunidades a sus aprendices, desde el patrocinio, la vinculación laboral, el emprendimiento o la extensión de programas por medio de especializaciones presenciales/virtuales o cursos complementarios.
      br
      br
      |No dejes pasar esta oportunidad. ¡Inscríbete ya!


  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 2. Justificación<br>del programa

    p El programa 
      b Tecnólogo Virtual en Animación Digital
      |, se creó para brindar al sector productivo de la industria del entretenimiento Digital la posibilidad de incorporar personal cualificado y calificado en el proceso de producción de productos audiovisuales animados con altas capacidades creativas y profesionales, con el fin de contribuir al desarrollo económico, social y tecnológico de su entorno y del país, así como también, para mejorar la competitividad y posicionamiento de esta industria.
      br
      br
      |El SENA es la única institución educativa que ofrece el programa con todos los elementos de formación profesional, sociales, tecnológicos y culturales, metodologías de aprendizaje innovadoras, acceso a tecnologías de última generación, estructurado sobre métodos más que contenidos, lo que potencia la formación de ciudadanos librepensadores, con capacidad crítica, solidarios y emprendedores, que lo acreditan y lo hacen pertinente y coherente con su misión, innovando permanentemente de acuerdo con las tendencias y cambios tecnológicos y las necesidades del sector empresarial y de los trabajadores, impactando positivamente la productividad, la competitividad, la equidad y el desarrollo del país.


  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 3. Población<br>objetivo

    p El programa Tecnólogo virtual en Animación Digital del SENA está dirigido a todas las personas que desean incursionar en la industria audiovisual, haciendo uso de sus habilidades creativas, narrativas y gerenciales, con el fin de desarrollar proyectos animados en 2D los cuales respondan a las necesidades y estándares de la industria creativa.

  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 4. Estrategia<br>metodológica

    p Centrada en la construcción de autonomía para garantizar la calidad de la formación en el marco de la formación por competencias, el aprendizaje por proyectos y el uso de técnicas didácticas activas que estimulan el pensamiento para la resolución de problemas simulados y reales dentro de la industria creativa; soportadas en el utilización de las tecnologías de la información y la comunicación, integradas, en ambientes virtuales de aprendizaje, que en todo caso recrean el contexto productivo y vinculan al aprendiz con la realidad cotidiana y el desarrollo de las competencias.  
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
