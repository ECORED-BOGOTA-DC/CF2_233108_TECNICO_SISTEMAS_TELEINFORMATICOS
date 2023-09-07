<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1 Gestión de la información
    .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5.mb-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema2/img1.png')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 La gestión de la información significa administrar adecuadamente la información, protegerla para que pueda recuperarse cuando sea necesario y evitar que se filtre. Es por esto que se hace necesario realizar una gestión de forma centralizada sobre la información interna utilizando herramientas adecuadas, ya que aunque algunas se especializan en facilitar la recuperación de información tienen problemas de seguridad y por ende, presentan riesgo de fuga de información. Por tanto, a la hora de gestionar la información es necesario tener en cuenta la compatibilidad entre la facilidad de extracción y uso de la información y la seguridad.
    .row.align-items-center.mb-5
      .col-lg-8.mb-4.mb-lg-0
        p.mb-0 Mientras los escándalos de fugas de información corporativa continúan día tras día, muchos dueños de negocios deben entender que esto no es un incendio al otro lado del río. En particular, incluso las pequeñas y medianas empresas, que hasta ahora solían quedar excluidas de los ciberataques, continúan sufriendo daños debido a los ataques indiscriminados. En tales circunstancias, ¿qué tipo de gestión de la información se requiere de las empresas? Diariamente se genera y gestiona diversa información en las empresas. La cantidad de datos de ventas, datos de ventas, datos de compras, datos de clientes, materiales de reuniones, documentos de aprobación, planes comerciales, etc. es enorme. Dicha información a menudo incluye información personal e información confidencial, y nunca debe filtrarse fuera de la empresa. Sin embargo, de vez en cuando, los activos de información de una empresa pueden sufrir daños como fugas, daños o desaparición., los cuales se tienden a pensar en ellas como incidentes causados por ataques cibernéticos, pero, en realidad, los factores internos como pérdida/extravío, mal funcionamiento y mala gestión representan por sí solos altos porcentajes de errores internos.
      .col-lg-4
        figure
          img(src='@/assets/curso/tema2/img2.png', style="width: 370px", alt='').m-auto
    .bloque-texto-g.color-acento-botones.p-3.p-sm-4.p-md-5.mb-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema2/img3.png')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 Es cierto que muchas empresas se han beneficiado de la difusión de las computadoras personales en los hogares en general, el desarrollo de entornos de Internet de alta velocidad y el aumento explosivo de usuarios de teléfonos inteligentes. Por otro lado, sin embargo, también es cierto que pueden producirse incidentes de fuga de información por ligeros errores de gestión o por laxitud de la seguridad. En estas circunstancias, en lo que deben trabajar las empresas es en tomar las medidas de seguridad adecuadas y conocer con precisión el tipo, la calidad y la cantidad de los activos de información que posee la empresa. Esto ahora se posiciona como una de nuestras responsabilidades sociales. Además de las medidas de seguridad, las empresas necesitan trabajar en planes comerciales y presupuestos para el próximo año fiscal, trabajo diario de gestión y servicio al cliente, y no quedan muchos recursos excedentes. Especialmente para las pequeñas y medianas empresas, hay muchos casos en los que no se pueden tomar medidas de seguridad suficientes desde un punto de vista financiero. Es por eso que no se puede esperar incidentes de fuga de información. Por lo tanto, lo que debe considerar activamente es una contramedida que refuerce las medidas de seguridad mientras se usa los servicios de otras compañías.
    .row.justify-content-center.mb-5
      .col-lg-10
        .row.align-items-center
          .col-xl-7.bg-c3.p-4
            p.text-white.mb-0 Recientemente, se han proporcionado varios servicios web y también se proporcionan muchos sistemas comerciales que son indispensables para las actividades de gestión. Muchos de estos servicios web cumplen con altos requisitos de seguridad y, en algunos casos, las medidas de seguridad pueden reforzarse simplemente usándolos.
          .col-xl-auto
            figure.fig-p1
              img(src='@/assets/curso/tema1/img10.svg', style="width: 50px", alt='').m-auto
          .col-xl-4 
            figure
              img(src='@/assets/curso/tema2/img1.svg', style="width: 380px", alt='').m-auto
    .cajon.color-acento-botones.p-4.mb-3
      p.mb-0 Al utilizar los servicios web, muchas pequeñas y medianas empresas no solo buscan reducir la carga operativa y la inversión inicial, sino que también están considerando fortalecer las medidas de seguridad. En casos extremos, si todos los sistemas comerciales internos se convierten en servicios web, solo eso puede proporcionar suficientes medidas de seguridad. A través de prueba y error, incluso las pequeñas y medianas empresas pueden satisfacer completamente los requisitos de alta seguridad. Otro método efectivo es utilizar la subcontratación para crear recursos humanos y de tiempo internos y asignarlos a medidas de seguridad.

</template>

<script>
export default {
  name: 'Tema2',
  data: () => ({
    // variables de vue
  }),
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
  updated() {
    this.$aosRefresh()
  },
}
</script>

<style lang="sass"></style>
