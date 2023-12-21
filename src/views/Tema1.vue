<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Ensayo    
  
    .row
      .col-xl-12
    #t_1_1.titulo-segundo.color-acento-contenido(data-aos="zoom-in-left")
      h2.my-5 1.1 Definición    
    .row.justify-content-center.align-items-center.mb-5
      .col-lg-5
        figure
          img(src='@/assets/curso/temas/tema1/img1.jpg', alt='Imagen decorativa')

      .col-lg-7
        .cajon.color-primario.p-4.mb-4
          p El ensayo, considerado un género literario, es un escrito libre que explora y expone argumentos y reflexiones sobre un tema de interés. Según la Real Academia Española (RAE), se caracteriza por desarrollar ideas sin necesidad de mostrar un aparato erudito.
        p Los ensayos permiten al autor expresar opiniones basadas en investigaciones y conocimientos personales, sin restricciones estructurales rígidas. Su estructura común incluye introducción, desarrollo y conclusión, proporcionando una plataforma para la manifestación de ideas y opiniones de manera creativa y persuasiva. La definición de la RAE destaca que el ensayo es un escrito en prosa que describe, aclara, argumenta o analiza un tema específico, donde el autor desarrolla ideas con carácter y estilo personal. La efectividad del ensayo se vincula a una estructura eficaz que facilita la claridad para el lector. Las características esenciales del ensayo incluyen basarse en investigación, expresar subjetividad, aplicar normas APA en citación y referenciación, y mantener coherencia gramatical.

    Separador    
    .row
      .col-xl-12
    #t_1_2.titulo-segundo.color-acento-contenido(data-aos="zoom-in-left")
      h2.my-5 1.2 Estructura del ensayo
    .row.justify-content-center.align-items-center.mb-5
      .col-lg-8
        ol.lista-ol--cuadro
          li
          .lista-ol--cuadro__vineta
            span 1
          | #[b Título]: se escribe al inicio del escrito, debe ser claro, corto y conciso; además, de ser atrayente para el lector.
          li
          .lista-ol--cuadro__vineta
            span 2
          | #[b Introducción]: el propósito de la introducción es darle al lector una idea clara de lo que tratara el ensayo. Debe proporcionar información básica sobre el problema o asunto específico que está abordando y debe describir claramente un argumento.
          li
          .lista-ol--cuadro__vineta
            span 3
          | #[b Tesis]: se indica la idea que el autor desea defender frente al tema que va a tratar y se redacta al final de la introducción como una postura personal.
          li
          .lista-ol--cuadro__vineta
            span 4
          | #[b Desarrollo]: es donde se presentan los argumentos que defienden la postura que se tuvo en la tesis, con respecto al tema a tratar. Cada párrafo del cuerpo debe contener una idea o afirmación clave, que esté respaldada por ejemplos relevantes y evidencia del cuerpo de trabajo académico sobre el tema escogido (es decir; libros académicos o artículos de revistas).
          li
          .lista-ol--cuadro__vineta
            span 5
          | #[b Conclusión]: es realizar una reflexión final, donde se resumen brevemente los argumentos clave abordados en el ensayo. 
          li
          .lista-ol--cuadro__vineta
            span 6
          | #[b Referencias bibliográficas]: es una lista ordenada alfabéticamente de todas las fuentes utilizadas. Esta lista se encuentra al final del trabajo y permite al lector verificar la veracidad de las declaraciones y / o cifras presentadas en el ensayo. También permite que un escritor dé el crédito adecuado a las citas o frases clave para evitar el plagio. Debe guardar la citación establecida según las normas APA vigentes.
      .col-lg-4
        figure
          img(src='@/assets/curso/temas/tema1/img2.svg', alt='Imagen decorativa')
    
    Separador
    .row
      .col-xl-12
    #t_1_3.titulo-segundo.color-acento-contenido(data-aos="zoom-in-left")
      h2.my-5 1.3 Pasos para elaborar un ensayo
    
    .tarjeta.tarjeta--gris.p-4
      PasosB.color-primario
        .row(titulo="Paso 1")
          .col-md-6.mb-4.mb-md-0
            h3 Lectura
            p Se sugiere llevar a cabo una lectura exhaustiva sobre los temas de interés en el caso de un ensayo libre, o sobre los requerimientos establecidos si se ha especificado un tema en particular.
        
          .col-md-6
            figure
              img(src='@/assets/curso/temas/tema1/img3.jpg', alt='Imagen decorativa')
        .row(titulo="Paso 2")
          .col-md-6.mb-4.mb-md-0
            h3 Tipo de ensayo
            p Debe definirse el tipo de ensayo a abordar, considerando las siguientes categorías:
            .cajon.colorpaso.p-4.mb-4              
              ul.lista-ul
                li
                  i.fas.fa-circle(style="color:#E6FF48;")
                  | #[b Crítico]: donde indica su postura crítica frente al tema planteado.
                li
                  i.fas.fa-circle(style="color:#E6FF48;")
                  | #[b Filosófico]: a través de un tema que aborde los valores y principios éticos que desarrolla la idea.
                li
                  i.fas.fa-circle(style="color:#E6FF48;")
                  | #[b Bibliográfico]: aquel que se aborda a partir de las vivencias personales; es decir, se habla sobre sí mismo.
                li
                  i.fas.fa-circle(style="color:#E6FF48;")
                  | #[b Expositivo]: se expone un tema a partir de sus conocimientos.
                li
                  i.fas.fa-circle(style="color:#E6FF48;")
                  | #[b Argumentativo]: a través de argumentos defiende la postura que está dando frente al tema desarrollado.
                li
                  i.fas.fa-circle(style="color:#E6FF48;")
                  | #[b Científico]: basado en datos científicos se desarrolla el escrito.
                li
                  i.fas.fa-circle(style="color:#E6FF48;")
                  | #[b Literario]: aquel que se basa en el arte al momento de desarrollar las ideas en el escrito.

        
          .col-md-6
            figure
              img(src='@/assets/curso/temas/tema1/img4.jpg', alt='Imagen decorativa')
        .row(titulo="Paso 3")
          .col-md-6.mb-4.mb-md-0
            h3 Lluvia de ideas
            p Se trata de un esquema de las ideas principales antes de escribir.
        
          .col-md-6
            figure
              img(src='@/assets/curso/temas/tema1/img5.jpg', alt='Imagen decorativa')
        .row(titulo="Paso 4")
          .col-md-6.mb-4.mb-md-0
            h3 Construcción de la tesis
            p Se aconseja redactar la tesis (argumento principal) del ensayo, debido a que es un elemento crucial. Debe destacarse como un punto fuerte.
        
          .col-md-6
            figure
              img(src='@/assets/curso/temas/tema1/img6.jpg', alt='Imagen decorativa')
        .row(titulo="Paso 5")
          .col-md-6.mb-4.mb-md-0
            h3 Escribir
            p Se inicia escribiendo en uno o dos párrafos el desarrollo de la primera idea que argumenta la tesis, respaldando cada párrafo con investigación, hechos, ejemplos, una anécdota (una breve historia personal), o algún tipo de justificación descriptiva.
            P Los siguientes párrafos se generan desarrollando cada idea y finalmente se concluyen los argumentos expuestos.

        
          .col-md-6
            figure
              img(src='@/assets/curso/temas/tema1/img7.jpg', alt='Imagen decorativa')
        .row(titulo="Paso 6")
          .col-md-6.mb-4.mb-md-0
            h3 Título
            p El título debe ser atrayente (atractivo), con el fin de motivar al lector a iniciar la lectura.
        
          .col-md-6
            figure
              img(src='@/assets/curso/temas/tema1/img8.jpg', alt='Imagen decorativa')
        .row(titulo="Paso 7")
          .col-md-6.mb-4.mb-md-0
            h3 Extensión
            p La extensión del ensayo se caracteriza por no ser muy extensa, por lo tanto, no debería exceder las tres páginas. Sin embargo, es crucial que las ideas sean concretas para evitar ampliar demasiado el tema tratado.
        
          .col-md-6
            figure
              img(src='@/assets/curso/temas/tema1/img9.jpg', alt='Imagen decorativa')
        .row(titulo="Paso 8")
          .col-md-6.mb-4.mb-md-0
            h3 Subjetividad
            p Por más datos investigados sobre el tema a desarrollar en el ensayo, se debe tener en cuenta que siempre la postura debe ser personal y es necesario dejarlo claro en el escrito.
        
          .col-md-6
            figure
              img(src='@/assets/curso/temas/tema1/img10.jpg', alt='Imagen decorativa')
        .row(titulo="Paso 9")
          .col-md-6.mb-4.mb-md-0
            h3 Referentes bibliográficos
            p Al final del documento referencia a los autores que cito en el documento.
        
          .col-md-6
            figure
              img(src='@/assets/curso/temas/tema1/img11.jpg', alt='Imagen decorativa')
        .row(titulo="Paso 10")
          .col-md-6.mb-4.mb-md-0
            h3 Revisión
            p Se debe leer atentamente el ensayo para corregir todos los errores gramaticales y ortográficos.
            .cajon.colorpaso.p-4.mb-4              
              ul.lista-ul
                li
                  i.fas.fa-circle(style="color:#E6FF48;")
                  | Investigar sobre el tema a tratar en el ensayo.
                li
                  i.fas.fa-circle(style="color:#E6FF48;")
                  | Abordar temas que pueda defender mediante una postura clara.
                li
                  i.fas.fa-circle(style="color:#E6FF48;")
                  | Plantear una tesis que impacte y genere deseos por parte del lector de conocer los argumentos que la soportan.
                li
                  i.fas.fa-circle(style="color:#E6FF48;")
                  | Recordar que habrá un lector del ensayo, por este motivo no debe abordarse ideas que solo el autor entendería.
                li
                  i.fas.fa-circle(style="color:#E6FF48;")
                  | Apoyarse en un lector externo para conocer las apreciaciones sobre el escrito.
                li
                  i.fas.fa-circle(style="color:#E6FF48;")
                  | Antes de entregar el ensayo, revisar nuevamente el escrito para corregir errores gramaticales y metodológicos.
                li
                  i.fas.fa-circle(style="color:#E6FF48;")
                  | Aplicar los aspectos solicitados por el instructor al momento de realizar el ensayo.
        
          .col-md-6
            figure
              img(src='@/assets/curso/temas/tema1/img12.jpg', alt='Imagen decorativa')
    Separador
    .row
      .col-xl-12
    #t_1_4.titulo-segundo.color-acento-contenido(data-aos="zoom-in-left")
      h2.my-5 1.4 Herramientas digitales se pueden utilizar para la elaboración de un ensayo
    
    SlyderF.mb-5(columnas="col-lg-6 col-xl-4")
      .tarjeta.color-primario.p-4
        .row.justify-content-center.mb-3
          .col-8
            img(src='@/assets/curso/temas/tema1/img13.svg' alt='AvatarTop')
        h4.text-center Microsoft Word
        p.text-center Es quizás la herramienta principal que se utiliza al momento de redactar un ensayo de manera digital, esta herramienta tiene la posibilidad ayudar un poco al escritor en la ortografía.
      .tarjeta.color-primario.p-4
        .row.justify-content-center.mb-3
          .col-8
            img(src='@/assets/curso/temas/tema1/img14.svg' alt='AvatarTop')
        h4.text-center Adobe IlIustrador
        p.text-center Si el autor del ensayo tiene practicidad en esta herramienta, puede ser una manera muy novedosa de presentar uno, ya que por medio de ella se podría dar una división de columnas, utilización de gráficos y diagramación textual. De igual manera, si utiliza otra a través de la cual pueda relacionar un escrito la puede utilizar.
      .tarjeta.color-primario.p-4
        .row.justify-content-center.mb-3
          .col-8
            img(src='@/assets/curso/temas/tema1/img15.svg' alt='AvatarTop')
        h4.text-center Corrector Online
        p.text-center Revisión y mejora de gramática de textos https://www.correctoronline.es/ 
      .tarjeta.color-primario.p-4
        .row.justify-content-center.mb-3
          .col-8
            img(src='@/assets/curso/temas/tema1/img16.svg' alt='AvatarTop')
        h4.text-center Language Tool
        p.text-center Revisión de ortografía y estilo. https://languagetool.org/es
      .tarjeta.color-primario.p-4
        .row.justify-content-center.mb-3
          .col-8
            img(src='@/assets/curso/temas/tema1/img17.svg' alt='AvatarTop')
        h4.text-center Cite
        p.text-center Generador automático de referencias bibliográficas, en formato APA  https://www.cite.com/
    .row
      .col-xl-12
    #t_1_5.titulo-segundo.color-acento-contenido(data-aos="zoom-in-left")
      h2.my-5 1.5 Ejemplo de un ensayo
    .row.justify-content-center.align-items-center
      .col-lg-10.col-md-4.mb-md-0(data-aos="flip-left")
        .titulo-sexto.color-acento-contenido.offset-0
          h5 Figura 1.
          span  #[i  Ensayo]
    .row.justify-content-center.align-items-center.mb-5
      .col-lg-10.desktop(data-aos="flip-up")
        figure
          img(src='@/assets/curso/temas/tema1/img18.png', alt='Ensayo')          

</template>

<script>
export default {
  name: 'Tema1',
  components: {},
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
